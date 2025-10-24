# Sistema de Recomendação de Filmes 🎬

Projeto simples de **Machine Learning** desenvolvido no **Google Colab** para demonstrar o uso de **filtragem colaborativa** baseada em similaridade entre usuários.

---

## Objetivo
Recomendar filmes a um usuário com base nas preferências de outros usuários semelhantes.  
Exemplo: se dois usuários deram notas parecidas para vários filmes, é provável que gostem das mesmas recomendações.

---

## Técnicas utilizadas
- **Pandas** — manipulação dos dados  
- **Scikit-learn** — cálculo de similaridade do cosseno  
- **Seaborn / Matplotlib** — visualização da matriz de notas  

---

## Estrutura do projeto
1. Criação de um dataset simples de usuários, filmes e notas.  
2. Geração da matriz **usuário × filme**.  
3. Cálculo de **similaridade do cosseno** entre os usuários.  
4. Função de recomendação que sugere filmes ainda não avaliados.  
5. Visualização opcional em **heatmap**.

---

## Como executar
1. Abra o arquivo `Recomendacao_Filmes.ipynb` no **Google Colab**.  
2. Execute as células em sequência (Shift + Enter).  
3. Teste a recomendação alterando o nome do usuário no final do código:
   ```python
   recomendar("Carla")
