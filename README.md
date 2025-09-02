📌 Projeto: Processamento de Imagens com EC2 + EBS
📖 Descrição

Este projeto tem como objetivo processar imagens na nuvem utilizando serviços da Amazon Web Services (AWS).
O processamento acontece em uma instância EC2 (computador virtual) e as imagens são armazenadas em um volume EBS (disco virtual).

Com isso, conseguimos criar uma infraestrutura escalável para:

Armazenar imagens originais.

Processar essas imagens (redimensionar, aplicar filtros, reconhecimento, etc.).

Guardar os resultados no armazenamento persistente.




🏗 Arquitetura do Projeto

1- EC2 (Elastic Compute Cloud):

 Responsável pelo processamento.


2- EBS (Elastic Block Store):

 Volume anexado à EC2.
 Armazena imagens originais e processadas.

🔄 Fluxo do Processo

1- Criar instância EC2.

2- Criar e anexar EBS à instância.

3- Fazer upload das imagens para o EBS.

4- Executar scripts de processamento no EC2.

Armazena imagens originais e processadas.
