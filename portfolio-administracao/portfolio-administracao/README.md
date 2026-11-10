# Portfólio Profissional de Administração

Site estático desenvolvido com **HTML5, CSS3 e JavaScript puro**, sem banco de dados, framework ou etapa de compilação.

## 1. Como executar

1. Extraia o arquivo ZIP para uma pasta do computador.
2. Abra a pasta `portfolio-administracao` no Visual Studio Code.
3. Abra o arquivo `index.html` no navegador.

**Opção recomendada:** instale a extensão **Live Server** no VS Code, clique com o botão direito em `index.html` e selecione **Open with Live Server**. O navegador abrirá o site e atualizará a página quando você salvar alterações.

Não é necessário executar `npm install`, `npm start` ou configurar backend.

## 2. Estrutura de pastas

```text
portfolio-administracao/
├── index.html
├── README.md
├── css/
│   └── style.css
└── js/
    └── script.js
```

- `index.html`: conteúdo e estrutura das seções.
- `css/style.css`: identidade visual, layout, cores e responsividade.
- `js/script.js`: menu para dispositivos móveis e ano automático.
- `README.md`: instruções de execução e personalização.

## 3. Personalização obrigatória

Antes de publicar, abra `index.html` e substitua os textos de exemplo:

- `Seu Nome`, formação, cidade e resumo profissional.
- Instituições, cursos, certificações e respectivos anos.
- Competências: mantenha somente as que você realmente domina.
- Empresas, cargos, períodos e atividades profissionais.
- Os três projetos demonstrativos por trabalhos reais ou acadêmicos que você realizou.
- E-mail e endereço do LinkedIn.

Use a busca do VS Code (`Ctrl + F`) para localizar termos como `Seu Nome`, `20XX`, `exemplo.com` e `seu-usuario`.

### Sobre os projetos de exemplo

Os três projetos incluídos são **modelos fictícios/demonstrativos** para mostrar como preencher os campos exigidos. Os valores do projeto financeiro também são hipotéticos. Não os apresente como resultados reais. Troque-os por projetos próprios e informe resultados medidos; quando não houver medição, descreva o resultado qualitativo sem inventar percentuais.

## 4. Regras de negócio atendidas

| Regra | Implementação |
|---|---|
| RN01 | Apresentação pessoal com resumo editável |
| RN02 | Três projetos com objetivo, problema, ações e resultado |
| RN03 | Área administrativa identificada em cada projeto |
| RN04 | Espaços para indicadores e resultados mensuráveis |
| RN05 | Competências técnicas e comportamentais separadas |
| RN06 | Formação, cursos, instituição e ano |
| RN07 | Experiências organizadas da mais recente para a mais antiga |
| RN08 | Projeto com 5W2H, fluxograma e projeto com SWOT |
| RN09 | Projeto com fluxo de caixa simplificado |
| RN10 | E-mail e LinkedIn; orientação para não publicar dados sensíveis |
| RN11 | Identidade visual consistente |
| RN12 | Layout responsivo para celular e computador |
| RN13 | Aviso sobre autorização e anonimização de dados empresariais |
| RN14 | Recomenda-se revisão e atualização semestral |

## 5. Observações técnicas

- Não há banco de dados. As informações ficam escritas diretamente no HTML.
- Não há formulário de contato com envio; os contatos usam `mailto:` e link do LinkedIn.
- A fonte é carregada do Google Fonts. Sem internet, o navegador usará uma fonte substituta.
- Para publicar, envie a pasta para um serviço de hospedagem de site estático, como GitHub Pages ou Netlify.
- Não publique CPF, endereço residencial completo, documentos, senhas ou dados confidenciais de empresas.

## 6. Checklist antes de entregar/publicar

- [ ] Preencher apresentação pessoal e resumo (até 10 linhas).
- [ ] Revisar formação, cursos e certificações.
- [ ] Conferir competências e experiências.
- [ ] Documentar pelo menos três projetos próprios.
- [ ] Incluir ferramenta de gestão e análise financeira simples.
- [ ] Validar todos os resultados e indicadores.
- [ ] Atualizar e testar e-mail e LinkedIn.
- [ ] Revisar ortografia e gramática.
- [ ] Testar no celular e no computador.
- [ ] Remover informações pessoais sensíveis e dados empresariais não autorizados.
