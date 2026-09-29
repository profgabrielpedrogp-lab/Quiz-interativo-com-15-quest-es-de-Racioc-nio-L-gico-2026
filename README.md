# 🎯 Quiz LIDERA Concursos - Raciocínio Lógico

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34C26?style=flat&logo=html5&logoColor=white)](https://www.w3.org/html/)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://www.w3.org/Style/CSS/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://www.javascript.com/)

## 📝 Descrição

Quiz interativo com **15 questões de Raciocínio Lógico** desenvolvido para a **LIDERA Concursos**, ministrado pelo Professor Gabriel Pedro. 

O projeto oferece uma experiência de aprendizado dinâmica com interface elegante, gabarito comentado e análise detalhada de cada resposta.

## ✨ Características

- ✅ **15 Questões de Raciocínio Lógico** - Uma por vez
- ✅ **Design Responsivo** - Funciona em desktop, tablet e celular
- ✅ **Gabarito Interativo** - Clique para revelar a resposta correta
- ✅ **Análise Detalhada** - Explicação de cada resposta
- ✅ **Barra de Progresso** - Acompanhe seu progresso
- ✅ **Logo LIDERA** - Branding profissional
- ✅ **Sem Dependências** - Funciona com HTML, CSS e JavaScript puro
- ✅ **Fácil de Usar** - Interface intuitiva

## 🎓 Tópicos Abordados

1. **Lógica Proposicional** - Premissas e conclusões válidas
2. **Silogismos** - Raciocínio dedutivo
3. **Relações Lógicas** - Parentesco e relações
4. **Quantificadores** - Universal (∀) e Existencial (∃)
5. **Teoria dos Conjuntos** - União, interseção e diferença
6. **Diagramas de Venn** - Representação visual
7. **Proposições Condicionais** - Se...então e contrapositiva
8. **Negação Lógica** - Operações com negação

## 🚀 Como Usar

### Opção 1: Abrir Localmente
1. Clone ou baixe o repositório
2. Abra o arquivo `quiz_lidera.html` no seu navegador
3. Comece a responder as questões!

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/quiz-lidera-concursos.git

# Navegue até o diretório
cd quiz-lidera-concursos

# Abra o arquivo HTML no navegador (ou clique duas vezes)
open quiz_lidera.html  # macOS
start quiz_lidera.html  # Windows
xdg-open quiz_lidera.html  # Linux
```

### Opção 2: Usar Online
- Hospede o arquivo em qualquer servidor web
- Ou use serviços como GitHub Pages, Vercel, Netlify

## 📋 Estrutura do Projeto

```
quiz-lidera-concursos/
├── quiz_lidera.html       # Arquivo principal do quiz
├── README.md              # Este arquivo
└── assets/                # (Opcional) Logo e recursos
    └── logo.png
```

## 🎯 Questões do Quiz

### Exemplo de Questão:
**Questão 1:** Uma comissão de manutenção avaliou três equipamentos de uma autarquia com base nas seguintes premissas...

- **Opção A:** O gerador recebeu selo de conformidade. ✓ (Gabarito)
- **Opção B:** O gerador foi liberado para uso imediato.
- **Opção C:** O gerador dispensará nova manutenção.
- **Opção D:** O gerador não apresentou falha alguma.
- **Opção E:** O gerador possui desempenho satisfatório.

**Análise:** Se um equipamento é aprovado na inspeção, ele recebe um selo de conformidade...

## 🎨 Paleta de Cores

| Cor | Código | Uso |
|-----|--------|-----|
| Dourado | `#d4af37` | Destaque, logo, progresso |
| Azul Escuro | `#1a1a2e` | Fundo principal |
| Azul Médio | `#16213e` | Fundo gradiente |
| Branco | `#ffffff` | Texto principal |
| Cinza | `#aaa` | Texto secundário |

## 💻 Tecnologias

- **HTML5** - Estrutura semântica
- **CSS3** - Estilização e animações
- **JavaScript Vanilla** - Interatividade (sem bibliotecas)

## 📱 Responsividade

O quiz é totalmente responsivo e funciona em:
- 🖥️ Desktop (1920px+)
- 💻 Laptop (1024px+)
- 📱 Tablet (768px+)
- 📲 Mobile (320px+)

## 🔧 Personalizações

Para adicionar novas questões, edite o array `questoes` no arquivo `quiz_lidera.html`:

```javascript
const questoes = [
    {
        numero: 1,
        texto: "Sua pergunta aqui...",
        opcoes: [
            "Opção A",
            "Opção B",
            "Opção C",
            "Opção D",
            "Opção E"
        ],
        gabarito: "Opção A",
        analise: "Sua análise aqui..."
    },
    // Adicione mais questões...
];
```

## 👨‍🏫 Professor

**Gabriel Pedro** - Professor de Raciocínio Lógico e Preparação para Concursos
- LIDERA Concursos
- Especialização em Lógica Proposicional e Argumentação

## 📄 Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.

## 🤝 Contribuições

Contribuições são bem-vindas! Por favor:

1. Faça um Fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## ✉️ Contato

Para dúvidas ou sugestões sobre o quiz, entre em contato:
- **Email:** gabriel.pedro@lideraconcursos.com.br
- **Site:** www.lideraconcursos.com.br
- **GitHub:** [@seu-usuario](https://github.com/seu-usuario)

## 📊 Estatísticas

- **Total de Questões:** 15
- **Tópicos Abordados:** 8
- **Tempo Estimado:** 30-45 minutos
- **Nível de Dificuldade:** Intermediário a Avançado

## 🎯 Objetivos Educacionais

Ao completar este quiz, o aluno será capaz de:
- ✓ Identificar proposições lógicas válidas
- ✓ Aplicar silogismos e raciocínio dedutivo
- ✓ Trabalhar com quantificadores (∀ e ∃)
- ✓ Compreender operações com conjuntos
- ✓ Resolver problemas de lógica proposicional
- ✓ Analisar argumentos e suas contrapositivas

## 🚀 Melhorias Futuras

- [ ] Adicionar modo escuro/claro
- [ ] Sistema de pontuação e ranking
- [ ] Exportar resultado em PDF
- [ ] Adicionar mais questões (30, 50, 100)
- [ ] Modo aleatório de questões
- [ ] Integração com banco de dados
- [ ] Sistema de usuário e histórico
- [ ] App mobile (React Native)

## 📸 Screenshots

### Tela Inicial
```
┌─────────────────────────────────────────────┐
│  [Logo LIDERA]                              │
│  Prof. Gabriel Pedro                        │
│  LIDERA Concursos                           │
│  Quiz de Raciocínio Lógico                  │
│  [Barra de Progresso]                       │
├─────────────────────────────────────────────┤
│  Questão 1 de 15                            │
│                                             │
│  Uma comissão de manutenção avaliou...      │
│                                             │
│  ○ Opção A                                  │
│  ○ Opção B                                  │
│  ○ Opção C                                  │
│  ○ Opção D                                  │
│  ○ Opção E                                  │
│                                             │
│  [Ver Gabarito] [Próxima →]                 │
└─────────────────────────────────────────────┘
```

## 📞 Suporte

Se encontrar algum problema:
1. Verifique se está usando um navegador moderno (Chrome, Firefox, Safari, Edge)
2. Limpe o cache do navegador
3. Abra um issue no GitHub com a descrição do problema
4. Inclua prints da tela se possível

## ⭐ Dê uma Estrela!

Se este projeto foi útil para você, por favor dê uma ⭐ no GitHub!

---

**Desenvolvido com ❤️ para a LIDERA Concursos**

*Última atualização: 2024*
