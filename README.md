# SQL Server Developer. Tuning Códigos com máximo desempenho.

- Por que aprender sobre Tuning de SQL?

  Precisamos nos preocupar com o tempo de respostas das consultas realizadas na base de dados.
  Varios fatores podem contribuir com o baixo desempenho, segue abaixo alguns exemplos:

  - 1 - Instruções mal escritas, ou não respeitando boas práticas de desenvolvimeto.
  - 2 - Colunas mal definidas ou ocupando espaços desnecessários.
  - 3 - Banco de dados alocados em um unico disco, concorrendo com o sistema operacional e com outros aplicativos.
  - 4 - Tabelas sem Indices, indices mal dimensionados ou obsoletos.
  - 5 - Conversão de dados desnecessários.

  Outros fatores de infraestrutura que influenciam:

  - 1 - Hardware mal dimensionado.
  - 2 - Instalação e configuração do sistema operacional.
  - 3 - Dimensionamento errados dos conjuntos de discos que farão parte do armazenamento.
  - 4 - Instalação e confirguração do gerenciador de banco de dados.
 
   Outros fatores que podem contribuir para o mal desempenho das querys:

   - 1 - Aumento da massa de dados
   - 2 - Aumento das conexões e usuários das aplicações
   - 3 - Aumento no número de dancos de dados compartilhado, em um mesmo servidor com os dados compartilhados.

  Tuning não é uma ciência exata.

  Porem alguns procedimentos podem auxiliar na busca pelo bom desempenho.

   - 1 - Monitorar o ambiente
   - 2 - Relatório de Status
   - 3 - Aplicar as técnicas em ambiente de teste.
   - 4 - Implementar em ambiente de produção. A implementação em produção deve ser realizada aos poucos.
   - 5 - O ciclo deve ser constante e realizado periodicamente.
 
  Abaixo veremos um pouco sobre <b>Configurações do ambiente, monitoramento de comandos, consultar plano de execução, criar bancos e tabelas e índices eficientes, entre outras...
  
<div> 
<p><a href="https://github.com/JosiTubaroski/Preparando_Ambiente/blob/main/README.md"> &nbsp; &nbsp;&nbsp; &nbsp; 1 - Downloads e Instalações</a></p>
</div> 

  



  
