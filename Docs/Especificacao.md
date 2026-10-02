# Especificação 

  

## Finalidade 

Produzir uma orientação jurídica inicial sobre produto com vício não 

reparado no prazo legal, usando apenas fontes selecionadas (RAG manual). 

  

## Público 

Estudante/profissional que vai revisar a orientação e, depois, um 

consumidor leigo. 

  

## Entradas permitidas 

apoio/caso_sanitizado.md, apoio/fonte_1.md, apoio/fonte_2.md. 

  

## Limites 

- Não usar dados pessoais reais ou do relato bruto. 

- Não afirmar nada que não esteja nas fontes (sem inventar leis ou julgados). 

- Não garantir resultado nem prometer indenização. 

- Não substitui advogado. 

  

## Critérios de aceitação 

1. Toda afirmação relevante cita arquivo e trecho. 

2. Afirmações sem apoio nas fontes aparecem como "NÃO CONSTA NAS FONTES". 

3. Nenhum dado pessoal aparece nas saídas. 

4. Existe verificação, auditoria em conversa separada e revisão humana. 

5. A orientação final traz limites e fontes. 

  

## Como outra pessoa reproduz este fluxo 

Ler o README, seguir a ordem das pastas, rodar docs/prompts/consulta_rag.md 

e depois auditoria.md em conversa nova, registrando tudo em evidencias/. 