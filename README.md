# Minha Biblioteca

Biblioteca pessoal pesquisável para organizar documentos e gravações, encontrar trechos e consultar a origem de cada resultado.

## Objetivo

Usar os créditos Azure restantes para processar o acervo e manter código, textos extraídos e transcrições exportáveis para uso local após o vencimento dos créditos.

## Escopo inicial

- Importar documentos e extrair texto com referência à página.
- Pesquisar trechos e filtrar por arquivo.
- Exportar os dados processados para continuar usando a biblioteca localmente.
- Integrar Azure AI Document Intelligence para documentos digitalizados.
- Adicionar transcrição de gravações com Azure Speech em uma etapa posterior.

Perguntas e respostas com fontes poderão ser adicionadas após validar a busca e a disponibilidade dos modelos na assinatura.

## Estado atual

Repositório inicializado. A aplicação e os recursos Azure ainda não foram implementados.

## Cuidados com o acervo

Arquivos pessoais, dados processados, credenciais e estado do Terraform devem permanecer fora do Git. As pastas `data/`, `uploads/`, `exports/` e `storage/` estão ignoradas.

## Próximas etapas

1. Construir a importação e a busca local com um pequeno conjunto de documentos.
2. Validar extração na Azure e medir o consumo antes de processar o acervo completo.
3. Exportar os resultados e documentar a execução local e a remoção dos recursos Azure.
