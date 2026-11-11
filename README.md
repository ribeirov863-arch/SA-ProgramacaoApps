# Da Ideia ao Código: Construção de Aplicações Funcionais

**Curso:** Técnico em Desenvolvimento de Sistemas  
**Unidade curricular:** Programação de Aplicativos  
**Situação de Aprendizagem (SA) nº 1**  
**Material comum às turmas da manhã e da tarde**

## Seu primeiro desafio como desenvolvedor

> Imagine que você acabou de entrar para a equipe de uma empresa de tecnologia.
> A empresa atende clientes de diferentes setores, e cada cliente deseja
> automatizar um processo ou resolver um problema.
>
> Seu papel é **escolher um desses clientes, entender sua necessidade e construir,
> etapa por etapa, um aplicativo funcional**.
> Você não precisa ter um projeto pronto: vamos começar pelo código, aprender a
> criar a interface e depois integrar um banco de dados.

**Escolha somente um projeto entre as dez opções previstas na SA:**

1. Delivery de comida
2. Aplicativo de transporte
3. Loja de departamentos
4. Streaming de vídeo
5. Gerenciamento de estoque
6. Hospital
7. Escola
8. Empresa de Recursos Humanos (RH)
9. Oficina mecânica
10. Fábrica de chocolate

Cada projeto tem particularidades. Pense no que o usuário desse sistema precisa
fazer, qual informação será recebida e qual resultado o aplicativo deve produzir.

Leia a **[Situação de Aprendizagem integral](documentos/SA_INTEGRAL.md)**.
O texto institucional está reproduzido nessa página, separado das orientações do professor.

## Como o projeto será desenvolvido?

| Etapa | Foco | Resultado a demonstrar |
| --- | --- | --- |
| **Bloco 2 — Entrega 1** | Código Python | Uma funcionalidade inicial executável; código-fonte organizado e comentado; testes e explicação da solução. |
| **Etapa de interface** | HTML, CSS e interação | Interface funcional relacionada ao projeto escolhido. |
| **Etapa de banco de dados** | Modelo relacional e SQL | Estrutura do banco e operações de cadastro, consulta, atualização e exclusão, conforme os requisitos. |
| **Etapa integradora** | Aplicação completa | Código, interface e banco integrados; documentação técnica e apresentação. |

**Na avaliação prática B2 será cobrado o código Python, não o HTML/CSS nem o banco de dados.**
As etapas seguintes serão orientadas ao longo das aulas. As datas, critérios
específicos e instrumentos de avaliação serão comunicados pelo professor.

### O que observar na Entrega 1 (B2)?

- Uma funcionalidade inicial adequada ao problema escolhido.
- Organização do código, nomes claros e comentários úteis.
- Aplicação de funções, classes ou módulos, quando apropriado ao problema.
- Execução e capacidade de explicar o que o programa faz.
- Testes e verificação de entradas inválidas, quando aplicável.

Esses itens sintetizam as capacidades do bloco; **não substituem o enunciado
nem os critérios de avaliação comunicados em aula**.

## Estrutura do repositório

```text
.
├── README.md
├── documentos/
│   └── SA_INTEGRAL.md
├── codigo/
│   └── app.py
├── interface/
│   ├── index.html
│   ├── style.css
│   └── script.js
├── banco_de_dados/
│   ├── estrutura.sql
│   └── crud.sql
└── .gitignore
```

**Todos os arquivos de código, interface e banco estão vazios propositalmente.**
Você desenvolverá seu próprio projeto. Não existe solução pronta nesse repositório.

- **`codigo/app.py`**: seu código Python.
- **`interface/`**: estrutura, estilo e comportamentos da interface.
- **`banco_de_dados/`**: definição das tabelas e comandos SQL do seu sistema.
- **`documentos/SA_INTEGRAL.md`**: enunciado e capacidades institucionais da SA.

A estrutura é um ponto de partida; o professor orientará possíveis ajustes.

## Como registrar e entregar seu trabalho

1. Leia a SA e selecione seu projeto.
2. No repositório-base, clique em **Use this template → Create a new repository**.
3. Crie **um repositório privado na sua própria conta**, com nome identificável para a disciplina.
4. Clone seu repositório individual no computador e trabalhe nos arquivos da etapa atual.
5. Faça `commit` e `push` no **seu próprio repositório**, registrando sua evolução.
6. Compartilhe o link com o professor e, se solicitado, convide-o como colaborador para acesso ao repositório privado.
7. Apresente a funcionalidade em execução e explique suas decisões técnicas.

> **Atenção:** não envie suas entregas à `main` do repositório-base do professor.
> Cada aluno terá histórico próprio, e os trabalhos não serão misturados.
> Em repositórios privados de contas pessoais, convidar alguém como colaborador
> também lhe concede permissão de escrita nesse repositório individual.

### Exemplos de mensagens de commit

- `docs: registra escolha do contexto`
- `feat: inicia primeira funcionalidade`
- `refactor: organiza funções e comentários`
- `test: verifica comportamento com entrada inválida`

## Conduta e cuidados

Desenvolva suas próprias soluções, teste o que escrever e esteja preparado para
explicar o código. Use dados fictícios e **não publique senhas, credenciais,
chaves de API nem dados pessoais reais**.

**Documento de referência:** [Situação de Aprendizagem nº 1 — Da Ideia ao Código](documentos/SA_INTEGRAL.md).
