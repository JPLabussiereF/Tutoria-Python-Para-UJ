# 🐍 Tutoria de Python - Engenharia da Computação

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Status](https://img.shields.io/badge/Status-Em%20Andamento-yellow?style=for-the-badge)
![Semestre](https://img.shields.io/badge/Semestre-1º-blue?style=for-the-badge)

*Material completo de Tutoria para estudantes de Sistemas de Informação e Análise e Desenvolvimento de Sistemas*

[🔗 Google Colab](https://colab.research.google.com/) | [📚 Python Essentials](https://www.netacad.com/courses/python-essentials-1?courseLang=pt-BR&instance_id=8493c744-f037-465e-bb0c-8e34467c36f5)

</div>

---

## 📋 Índice

- [Sobre o Repositório](#-sobre-o-repositório)
- [Estrutura dos Encontros](#-estrutura-dos-encontros)
- [Como Usar Este Material](#-como-usar-este-material)
- [Recursos Extras](#-recursos-extras)
- [Contribuindo](#-contribuindo)
- [Contato](#-contato)

---

## 🎯 Sobre o Repositório

Este repositório contém todo o material desenvolvido para a **Tutoria de Python** do curso de Engenharia da Computação. O conteúdo está organizado em encontros progressivos, começando do básico absoluto até conceitos intermediários de programação.

### 📚 Objetivos da Tutoria

- Ensinar Python do zero para estudantes de SI e ADS
- Fornecer material teórico enxuto e prático
- Oferecer exercícios graduais (básico → intermediário → avançado)
- Disponibilizar gabaritos comentados para autoaprendizagem
- Preparar os alunos para projetos reais

---

## 📖 Estrutura dos Encontros

Cada encontro possui **120 minutos** e segue o padrão:
- **10 min** - Revisão e objetivos
- **20 min** - Teoria enxuta
- **20 min** - Demonstrações práticas
- **35 min** - Prática guiada
- **30 min** - Lista de exercícios
- **5 min** - Revisão relâmpago

### 🗂️ Encontros Disponíveis

<details>
<summary><b>📌 Encontro 1: Algoritmos + Hello, World!</b></summary>

**Tópicos:**
- Conceitos fundamentais de algoritmos
- Primeiros passos com Python
- `print()` e `input()`
- Função `type()` para identificar tipos
- Variáveis e comentários

**Arquivos:**
- `ENCONTRO-1.md` - Material teórico completo
- `exercicios_encontro_1.py` - 6 exercícios graduais
- `gabarito_encontro_1.py` - Soluções comentadas
- `tarefa_de_casa_encontro_1.py` - Projeto "Cartão de Visita Digital"

</details>

<details>
<summary><b>📌 Encontro 2: Sintaxe, tipos e variáveis</b></summary>

**Tópicos:**
- Tipos básicos: `int`, `float`, `str`, `bool`
- Conversões: `int()`, `float()`, `str()`, `bool()`
- Concatenação vs vírgulas no `print()`
- Formatação de saída
- Erros comuns com tipos

**Arquivos:**
- `ENCONTRO-2.md` - Teoria e exemplos
- `exemplos_encontro_2.py` - Código demonstrativo
- `exercicios_encontro_2.py` - 7 exercícios + desafio
- `gabarito_encontro_2.py` - Soluções detalhadas
- `tarefa_de_casa_encontro_2.py` - "Conversor Universal de Medidas"

</details>

<details>
<summary><b>📌 Encontro 3: Operadores aritméticos, comparação e lógicos</b></summary>

**Tópicos:**
- Operadores aritméticos: `+`, `-`, `*`, `/`, `//`, `%`, `**`
- Operadores de comparação: `==`, `!=`, `<`, `>`, `<=`, `>=`
- Operadores lógicos: `and`, `or`, `not`
- Precedência de operadores
- Tabelas-verdade práticas

**Arquivos:**
- `ENCONTRO-3.md` - Material completo
- `EXTRA.md` - 13 exercícios extras de input e operadores
- `exemplos_encontro_3.py` - Demonstrações práticas
- `exercicios_encontro_3.py` - 8 exercícios + desafio
- `gabarito_encontro_3.py` - Gabarito comentado
- `tarefa_de_casa_encontro_3.py` - "Calculadora Científica com Validação"

</details>

<details>
<summary><b>📌 Encontro 4: Estruturas condicionais (if/elif/else)</b></summary>

**Tópicos:**
- Estrutura `if` para execução condicional
- `elif` para múltiplas condições
- `else` como fallback
- Indentação obrigatória em Python
- Condicionais aninhadas
- Validação de entrada

**Arquivos:**
- `ENCONTRO-4.md` - Teoria de condicionais
- `EXTRA.md` - 13 exercícios de estruturas condicionais
- `exercicios_encontro_4.py` - Lista de exercícios
- `gabarito_encontro_4.py` - Soluções com explicações
- `tarefa_de_casa_encontro_4.py` - "Sistema de Classificação de Filmes"

</details>

<details>
<summary><b>📌 Encontro 5: Laços de repetição (for/while)</b></summary>

**Tópicos:**
- Loop `for` com sequências
- Loop `while` com condições
- Função `range()` e suas variações
- `break` e `continue`
- Loops aninhados
- Boas práticas

**Arquivos:**
- `ENCONTRO-5.md` - Guia rápido de loops
- `exercicios_encontro_5.py` - 12 exercícios progressivos
- `gabarito_encontro_5.py` - Soluções práticas
- `tarefa_de_casa_encontro_5.md` - 8 exercícios para casa

</details>

---

## 💻 Como Usar Este Material

### Para Estudantes

1. **Clone o repositório:**
```bash
git clone https://github.com/JPLabussiereF/Tutoria-Python-Para-UJ.git
cd Tutoria-python
```

2. **Navegue pelos encontros em ordem:**
   - Comece pelo `Encontro-1/`
   - Leia o arquivo `.md` com a teoria
   - Pratique com os exercícios `.py`
   - Compare com o gabarito após tentar

3. **Estrutura de cada pasta:**
```
Encontro-X/
├── ENCONTRO-X.md                # 📖 Material teórico
├── exemplos_encontro_X.py       # 💡 Código demonstrativo
├── exercicios_encontro_X.py     # ✏️ Lista de exercícios
├── gabarito_encontro_X.py       # ✅ Soluções comentadas
├── Slides-Encontro-X            # 📕 Slides
└── tarefa_de_casa_encontro_X.py # 🏠 Projeto para casa
```

4. **Recursos online recomendados:**
   - Use o [Google Colab](https://colab.research.google.com/) para executar código online
   - Faça o curso [Python Essentials](https://www.netacad.com/courses/python-essentials-1?courseLang=pt-BR&instance_id=8493c744-f037-465e-bb0c-8e34467c36f5) como complemento

### Para Monitores

- Cada `ENCONTRO-X.md` contém:
  - ⏰ Cronograma detalhado de 120 minutos
  - 📚 Resumo teórico enxuto
  - 💻 Exemplos de código prontos
  - 👥 Prática guiada passo a passo
  - 📝 Lista de exercícios graduais
  - 🎯 Revisão relâmpago
  - ❌ Erros comuns e como evitá-los

---

## 🛠️ Recursos Extras

### 📂 Git e GitHub

Tutoriais completos sobre versionamento e colaboração:

```
Git/
└── README.md              # Guia de instalação e comandos Git

GitHub/
├── README.md              # Tutorial GitHub passo a passo
├── FERRAMENTAS-E-RECURSOS.md  # Badges, stats, geradores
└── TEMPLATE-README.md     # Templates prontos para perfil
```

**Aprenda:**
- Como instalar e configurar Git
- Comandos essenciais do Git
- Criar conta e repositórios no GitHub
- Fazer Pull Requests
- Criar README de perfil profissional
- Usar badges, stats e recursos visuais

### 🎨 Recursos Visuais

- **Badges de tecnologias** prontos para copiar
- **GitHub Stats** automáticos
- **Templates de README** para iniciantes e avançados
- **Geradores automáticos** de documentação

---

## 📊 Progresso do Curso

```python
progresso = {
    "✅ Encontro 1": "Algoritmos + Hello World",
    "✅ Encontro 2": "Tipos e Variáveis", 
    "✅ Encontro 3": "Operadores",
    "✅ Encontro 4": "Estruturas Condicionais",
    "✅ Encontro 5": "Laços de Repetição",
}
```

---

## 🎓 Metodologia de Ensino

### Teoria Enxuta
- Conceitos explicados de forma clara e direta
- Glossário de termos técnicos
- Evita sobrecarga de informação

### Prática Intensa
- Exemplos executáveis em todos os encontros
- Exercícios do básico ao avançado
- Projetos práticos semanais

### Aprendizagem Ativa
- Prática guiada passo a passo
- Desafios extras para alunos rápidos
- Gabaritos comentados para autoaprendizagem

---

## 🤝 Contribuindo

Melhorias são sempre bem-vindas! Para contribuir:

1. **Fork** este repositório
2. **Crie** uma branch: `git checkout -b minha-contribuicao`
3. **Commit** suas alterações: `git commit -m 'feat: adiciona novo exercício'`
4. **Push** para a branch: `git push origin minha-contribuicao`
5. Abra um **Pull Request**

### 💡 Ideias de Contribuição

- Adicionar mais exercícios
- Corrigir erros ou typos
- Melhorar explicações
- Traduzir comentários
- Criar novos desafios

---

## 📧 Contato

- **Monitor:** [João Pedro Labussiere França](https://www.linkedin.com/in/joaolabussiere/)
- **Email:** [labussework@gmail.com](mailto:labussework@gmail.com)
- **GitHub:** [@JPLabussiereF](https://github.com/JPLabussiereF)

---

## 📜 Licença

Este material é disponibilizado para fins educacionais. Sinta-se livre para usar, modificar e distribuir, mantendo os créditos.

---

## ⭐ Agradecimentos

- Aos alunos de SI e ADS pela participação ativa
- À coordenação do curso pelo apoio à Tutoria
- À comunidade Python Brasil pelos recursos

---

<div align="center">

### 🚀 Bons estudos e bons códigos!

**"A única maneira de aprender programação é programando."**

---

![Python](https://img.shields.io/badge/Made%20with-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Markdown](https://img.shields.io/badge/Documented%20with-Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)
![Git](https://img.shields.io/badge/Versioned%20with-Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>