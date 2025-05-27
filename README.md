# 💓 Vem aferir — Monitoramento diário da pressão arterial

O **"Vem aferir"** é um projeto em Python desenvolvido com interface gráfica no Google Colab e banco de dados SQLite. Ele permite o **registro, análise e acompanhamento diário da pressão arterial**, ideal para pacientes que precisam levar relatórios para consultas médicas.

---

## ✅ Funcionalidades

- Registro diário da pressão sistólica (máxima) e diastólica (mínima)
- Seleção do dia da semana e sintomas como:
  - Dor de cabeça
  - Tontura
  - Enjoo
  - Visão embaçada
- 📅 **Data gerada automaticamente** com dia, mês e ano
- 📊 **Classificação automática da pressão arterial** com base em diretrizes clínicas:
  - Normal
  - Normal limítrofe
  - Hipertensão Estágio 1, 2 ou 3
  - Hipertensão sistólica isolada
- 💬 Recomendação personalizada com base nos valores inseridos
- Histórico completo com exibição em tabela (pandas)
- Opções para exclusão de registros (individuais ou todos)

---

## 🛠️ Tecnologias usadas

- Python 3
- Google Colab
- `ipywidgets` (interface gráfica)
- `SQLite3` (armazenamento dos dados)
- `pandas` (exibição em tabela)
- `datetime` e `locale` (formatação de datas)

---

## 🚀 Como usar

1. **Abra o projeto no Google Colab**
2. Execute as células na ordem indicada
3. Preencha os campos do formulário (pressão, sintomas, dia da semana)
4. Clique em **"Salvar dados"**
5. Visualize o histórico e o status atual da sua pressão

---

## 💡 Por que esse projeto é importante?

> "Vem aferir" nasceu da necessidade de acompanhar a própria saúde de forma organizada e digital. Mesmo sendo uma iniciante em programação, o projeto mostrou que é possível **criar soluções reais com Python**, mesmo com conhecimento básico.

Esse projeto incentiva outras pessoas iniciantes a aplicarem a programação para resolver problemas pessoais e melhorar a qualidade de vida.

---

## 📸 Exemplos

📍 Entrada de dados:  
- Pressão: 145 / 95  
- Sintomas: Dor de cabeça  
- Resultado: ⚠️ Hipertensão leve (Estágio 1)

📍 Histórico gerado:

| Data completa               | Dia da semana | Máxima | Mínima | Sintomas     | Classificação                                 |
|----------------------------|---------------|--------|--------|--------------|-----------------------------------------------|
| Segunda-feira, 27 de Maio  | Segunda-feira | 145    | 95     | Dor de cabeça| ⚠️ Hipertensão leve – Consulte seu médico.    |

---

## 🧩 Próximos passos

- Exportação para **PDF ou Excel**
- Geração de **gráficos com evolução da pressão**
- Interface web com Flask ou Streamlit
- Conexão com dispositivos de medição

---

## 👤 Autor

Desenvolvido por um(a) iniciante com apoio do ChatGPT da OpenAI.  
Um exemplo de como a tecnologia pode empoderar pessoas na busca por conhecimento e saúde.

---

## 📌 Licença

Este projeto é livre para uso pessoal e educacional. Sinta-se à vontade para contribuir ou adaptar.
