Processador de XML NF-e
Badge Badge

Este projeto consiste em uma ferramenta prática para processar arquivos XML de Notas Fiscais Eletrônicas (NF-e). Ele permite extrair dados relevantes, como valores de impostos, informações do emitente e destinatário, e gerar um arquivo Excel (.xlsx) organizado para análise.

📋 Funcionalidades
Upload de arquivos ZIP : Permite carregar múltiplos XMLs de NF-e compactados em um único arquivo ZIP.
Extração de dados :
Chave da NF-e
Valores de ICMS, PIS, COFINS e IPI
Dados do emitente e destinatário (CNPJ/CPF, nome, UF)
Resumos consolidados por CFOP, CST e alíquotas
Geração de Excel (.xlsx) : Exporta os dados extraídos para um arquivo Excel organizado e pronto para análise.
Feedback visual : Inclui um spinner de carregamento para indicar o progresso durante o processamento.
🛠️ Tecnologias Utilizadas
HTML/CSS : Interface simples e responsiva.
JavaScript : Lógica de processamento e interação com o usuário.
Bibliotecas :
JSZip : Para manipular arquivos ZIP.
SheetJS : Para gerar arquivos Excel (.xlsx).
