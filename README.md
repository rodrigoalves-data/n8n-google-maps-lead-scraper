# Google Maps Lead Scraper — n8n Workflow

Automação construída em n8n que gera leads a partir da Google Places API.

## O que faz

- Pesquisa negócios em múltiplas cidades automaticamente
- Extrai nome, morada, website, telefone e rating
- Remove duplicados
- Exporta tudo para o Google Sheets

## Resultado

101 leads em menos de 2 minutos.

## Como usar

1. Importa o ficheiro JSON no n8n
2. Cria uma API key na Google Cloud Console (Places API New)
3. Substitui a API key no nó Search Places1
4. No nó Lista Cidades define o teu nicho e cidades
5. Corre o workflow

## Requisitos

- n8n (cloud ou self-hosted)
- Google Places API key
- Google Sheets (opcional)

## Nota GDPR

Este workflow foi construído para fins de demonstração. Os dados recolhidos devem ser usados com propósito definido, não guardados indefinidamente, e apagados após o processo de prospeção. Consulta a legislação aplicável no teu país.

## Autor

Rodrigo Alves — [LinkedIn](https://www.linkedin.com/in/rodrigo-alves-5b4a0b3b9/) | [GitHub](https://github.com/rodrigoalves-data)
