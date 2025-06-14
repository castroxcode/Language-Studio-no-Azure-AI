# 🧠 Azure Speech Studio & Language Studio  
### Análise de Fala e Linguagem Natural com IA da Microsoft

Este repositório contém anotações, testes e insights adquiridos durante a exploração das ferramentas **Azure Speech Studio** e **Azure Language Studio**, com foco em soluções de **inteligência artificial voltadas para voz e linguagem natural**.

---

## 🔍 Objetivo

Explorar e compreender o funcionamento prático das ferramentas **Speech Studio** e **Language Studio**, utilizando os serviços de IA da Azure para:

- Transcrição de fala
- Síntese de voz (Text-to-Speech)
- Reconhecimento de intenção
- Análise de sentimentos
- Extração de entidades e palavras-chave
- Classificação de texto

---

## 🛠️ Ferramentas Utilizadas

| Ferramenta | Descrição |
|------------|-----------|
| **Azure Speech Studio** | Plataforma para serviços de fala: transcrição automática, síntese de voz, tradução e reconhecimento de intenção. |
| **Azure Language Studio** | Plataforma para análise de linguagem natural: análise de sentimentos, extração de entidades, resumo de texto, entre outros. |

---

## 🎙️ Azure Speech Studio – Principais Recursos Testados

### 1. Transcrição de Fala (Speech to Text)
- **Entrada:** Arquivos de áudio (WAV/MP3)
- **Saída:** Texto transcrito com timestamps e confiança
- **Observação:** A precisão é alta em áudios claros e com boa dicção; o reconhecimento em português é consistente, mas pode ser afetado por ruído.

### 2. Síntese de Voz (Text to Speech)
- Testes com vozes padrão e neural (voz mais natural e fluida).
- Possibilidade de **customizar vozes** e ajustar a **prosódia** com SSML (Speech Synthesis Markup Language).

### 3. Compreensão de Fala (Speech Intent Recognition)
- Integração com **Language Understanding (LUIS)** ou **Conversational Language Understanding** para identificar intenções em comandos de voz.
- Útil para construir **assistentes virtuais**, **chatbots falados** e **comandos de voz personalizados**.

---

## 🧠 Azure Language Studio – Principais Funcionalidades Testadas

### 1. Análise de Sentimento
- Classificação do texto em **positivo**, **negativo** ou **neutro**, com pontuação de confiança.
- Retorna análise por sentença e geral.
- **Insight:** Ideal para análise de feedbacks, reviews e redes sociais.

### 2. Extração de Entidades Nomeadas (NER)
- Identifica entidades como **nomes, locais, datas, valores monetários, organizações**, etc.
- Útil em automações e classificações automáticas de textos jurídicos, contratos, entre outros.

### 3. Palavras-Chave e Tópicos
- Extração de **termos relevantes** de um texto.
- Boa acurácia para textos objetivos, menos eficiente em textos muito genéricos.

### 4. Classificação de Texto Personalizada
- Possível treinar um modelo com exemplos rotulados para **categorizar textos automaticamente**.

---

## 💡 Insights e Boas Práticas

- **Speech Studio** funciona melhor com áudios de qualidade, sem ruídos e com boa dicção.
- **Language Studio** é poderoso para pré-processamento de textos e análises iniciais de sentimento ou entidades.
- Ambos podem ser integrados via API com aplicações web, bots, sistemas de atendimento e automações de backoffice.
- O uso de **SSML** permite customização avançada da leitura de textos pela voz sintética.
- Os recursos gratuitos permitem uma boa margem de testes, mas têm limitações de uso diário.

---

## ✍️ Conclusão

O uso combinado de **ferramentas de fala e linguagem da Azure** permite construir soluções inteligentes com alto potencial de automação, acessibilidade e análise textual.  
Este repositório reúne práticas fundamentais para começar a explorar essas soluções no contexto de **produtividade, atendimento, bots e análise de dados em linguagem natural**.
Se quiser, posso criar um exemplo real com arquivos .json ou .md para colocar nesse repositório também.
