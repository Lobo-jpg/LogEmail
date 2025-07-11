# Gerador de Variações de Email Profissional

Este projeto é uma ferramenta web que gera automaticamente **todas as variações possíveis** de um endereço de e-mail com pontos (.) inseridos em diferentes posições no nome de usuário.

Ideal para testes com serviços como Gmail, que ignoram pontos no nome do e-mail, e também para fins de automação ou organização.

## Como funciona

1. O usuário digita seu e-mail no campo indicado (ex: `joaosilva@gmail.com`).
2. O sistema gera diversas variações com pontos, como:
    - `joaosilva@gmail.com`
    - `joao.silva@gmail.com`
    - `j.o.a.o.s.i.l.v.a@gmail.com`
    - `j.oa.os.il.va@gmail.com`
3. As variações são exibidas na tela.
4. O usuário pode clicar em qualquer variação para copiá-la automaticamente.
5. Também é possível **baixar todas as variações em um arquivo .TXT**.

## Funcionalidades

- Interface moderna com **efeito vidro (glassmorphism)** e **animação de brilho (neon)**.
- Botões de **Gerar Variações**, **Resetar** e **Baixar .TXT**.
- Sistema de **alerta automático** caso o número de variações seja muito grande (acima de 4096).
- Caixa de **resultados com rolagem** e cópia com um clique.
- Totalmente feito com **HTML**, **CSS** e **JavaScript** puro.

## Tecnologias Utilizadas

- **HTML5**
- **CSS3** (incluindo animações e efeitos visuais)
- **JavaScript** (sem bibliotecas externas)

## Estrutura do Projeto

O projeto é composto por um único arquivo **HTML** com todo o conteúdo necessário (estilos, estrutura e scripts embutidos). Pode ser executado diretamente no navegador, sem instalação.

## Observações

- Este gerador funciona corretamente com domínios como **gmail.com**, onde os pontos no nome do e-mail são ignorados. Para outros provedores, o comportamento pode variar.
- **Não há envio ou armazenamento de informações.** Tudo é processado localmente no navegador.

## Autor

Desenvolvido por **LOBO NINTENDISTA**  
Projeto pessoal com foco em produtividade, automação e estilo visual moderno.
