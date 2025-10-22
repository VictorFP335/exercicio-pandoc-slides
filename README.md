
## Tarefa Prática: Github Actions

### Práticas - Grupo 10 

# Exercício 2 – Action Pandoc Markdown → PDF Slides

Este repositório contém um workflow do GitHub Actions que converte arquivos Markdown da pasta `docs/` em PDF de slides usando Pandoc.

## Estrutura
```
docs/
├── presentation.md
├── pandoc.yaml
.github/
└── workflows/
    └── slides.yml
```

## Funcionamento
- Ao dar push em um arquivo `.md` dentro de `docs/`, o workflow é acionado.
- O workflow instala Pandoc e LaTeX.
- O arquivo `presentation.md` é convertido para `slides.pdf`.
- O PDF é publicado como artefato.

## Entregas

- Capturas de tela da aba Actions mostrando execução bem-sucedida.

<img width="1874" height="588" alt="Captura de tela 2025-10-22 170914" src="https://github.com/user-attachments/assets/6fd3b865-f01e-444b-b874-908b71977837" />


## Licença

Este projeto está licenciado sob a licença MIT.  
Créditos: VictorFP335

