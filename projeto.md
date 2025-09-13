# TechJur

Sistema para Gerenciar Processos

> Gerenciar significa "organizar automaticamente"

- Acompanhar prazos
- Acessar informações importantes

## Informações Importantes

[GitHub](https://github.com/vhfedatto/techjur) | [Figma](https://www.figma.com/design/jHJhLAwsotismwD4AJIqY6/TechJur?node-id=0-1&p=f&t=WFiNRdpiFIihuEtc-0) | [Whimsical]()

## Requisitos do Sistema:

### 👨‍👩‍👧‍👦 **CADASTRO DE PESSOAS**
- Clientes;
- Partes envolvidas;
- Advogados;

> _Minha ideia é desenvolver um sistema em que o próprio escritório faz o cadastro dos seus advogados (ou compartilha com eles - tipo um whimsical) e de seus clientes._ 

> _Na hora de abrir um novo processo para ser gerido pelo sistema, você só precisa indicar a outra parte (pois o cliente e o advogado já estão cadastrados no seu sistema)._

> _Inclusive, poderia ter uma parte para já organizar a parte inicial da Petição Inicial automaticamente, juntando já todas as informações do cliente e do Advogado, precisando apenas indicar as informações do Réu._

---

### 💼 **GESTÃO DE PROCESSOS**
- **Cadastrar** → Indicar as informações básicas do processo.

| Tipos de Processo | Informações Básicas |
|----------------------|----------------------------|
| Todos | ID, tipo da ação, datas, status, partes |
| Petição Inicial | |
| Cível | |
| Trabalhista | |

- **Associação** → Associar (atribuir) o perfil do advogado e da parte defendida por ele. 1 advogado → n processos, 1 processo → n partes
- **Documentos** → Documentos que são anexados junto do documento do processo (principalmente petição - molde para procuração).

> _Minha ideia é: Na hora do cadastro, o responsável por isso, provavelmente o secretário do advogado, apenas clica no advogado, no cliente como autor, preenche as informações do réu (com base nas infos do processo), preenche as caixas de informações básicas do processo e o adiciona ao sistema._

> _Ao anexar documentos, digitar um título, uma breve descrição, data de anexo e por quem foi adicionado._

---

### 🏇 **GESTÃO DE ANDAMENTOS**

- Registrar os andamentos do processo.

> Isso implica dizer que:

- Adicionar uma data para o andamento, descrição e o advogado que registrou o andamento.

> Minha ideia é: