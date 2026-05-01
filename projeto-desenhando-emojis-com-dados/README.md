# 🎨 Desenhando Emojis com Dados

## 📝 Descrição do Projeto
Este projeto explora a manipulação de estruturas de dados complexas em Python, como **listas aninhadas, tuplas imutáveis e dicionários**. O objetivo é simular o processamento de imagens (filtros de brilho em pixels RGB) e a transposição de matrizes musicais.

Desenvolvido para consolidar o domínio sobre **loops aninhados (3 níveis)** e métodos fundamentais de coleções.

## 🚀 Tecnologias e Conceitos
* **Linguagem:** Python 3.x
* **Estruturas:** Dicionários (Mapas), Listas (Matrizes/Grades) e Tuplas (Pixels imutáveis).
* **Algoritmos:** * Processamento de Imagem: Aplicação de filtro de sombra em valores RGB.
    * Álgebra Linear: Transposição de matrizes 2x2 para arquivos de áudio.

## 🧩 Desafios Resolvidos

### 1. O Criador de Emojis (Pixels RGB)
Manipulação de uma grade 5x5 onde cada elemento é uma tupla `(R, G, B)`. O algoritmo identifica pixels amarelos e reduz seu brilho em 50%, gerando uma nova tupla para contornar a imutabilidade.

### 2. Matrizes Musicais
Processamento de uma biblioteca musical onde frequências sonoras estão organizadas em matrizes. Foi aplicada a técnica de **transposição**, invertendo linhas por colunas para alterar a melodia.

### 3. Integrador (Playlist de Imagens)
Criação de uma estrutura robusta que une metadados (Dicionários), sequências (Listas) e coordenadas fixas (Tuplas), utilizando métodos como `.update()`, `.pop()` e `.keys()`.

## 🔧 Como Executar
1. Clone o repositório.
2. Execute o script principal:
   ```bash
   python emojis_dados.py
