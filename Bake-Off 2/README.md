# Bake-off #2 — Seleção em UIs Densas (IPM)

Projeto desenvolvido no âmbito da UC de **Interação Pessoa-Máquina (2025/2026)**.

---

## Descrição

Este projeto consiste na otimização de uma interface densa com o objetivo de **minimizar o tempo de seleção de alvos** numa grelha de **80 elementos (8x10)**.

Foi fornecido um protótipo base em **p5.js**, que foi modificado para melhorar o desempenho do utilizador, mantendo as regras impostas pelo enunciado.  

O sistema mede automaticamente:
- taxa de sucesso (accuracy)  
- tempo total  
- tempo médio por alvo  
- tempo médio com penalização  

---

## Objetivo

Redesenhar a interface de forma a:
- reduzir o tempo de seleção  
- minimizar erros  
- melhorar a eficiência do utilizador  

---

## Funcionalidades Implementadas

- Interface com grelha de 80 alvos  
- Sistema de seleção otimizado  
- Melhorias na organização visual  
- Estratégias de destaque de alvos  
- Interação com rato (sem uso de teclado)  
- Registo automático de métricas de desempenho  

---

## Processo de Desenvolvimento

O projeto seguiu um processo iterativo:

### Iteração 1
- Análise do protótipo base  
- Identificação de problemas de usabilidade  
- Aplicação de princípios de UX  

### Iteração 2+
- Testes com utilizadores (N ≥ 10)  
- Medição de desempenho  
- Ajustes baseados em resultados  

Foram aplicados conceitos como:
- Leis de UX  
- Fatores humanos  
- Avaliação quantitativa  

---

## Restrições do Projeto

A solução teve de respeitar regras importantes:

- Não alterar cálculo de métricas nem Firebase  
- Não modificar labels dos alvos  
- Não usar teclado (apenas rato)  
- Não assumir conhecimento do alvo a selecionar  
- Interface adaptativa (mesmo tamanho em diferentes ecrãs)  

---

## Estrutura do Projeto

- `sketch.js` → lógica principal (p5.js)  
- `index.html` → interface web  
- `style.css` → estilos  
- `legendas/` → dados fornecidos (não alterados)  
- `README.md` → documentação  

---

## Como executar

### RECOMENDADO

Abrir no editor oficial:
```text
https://editor.p5js.org/
