# Metas APP 🎯

O incrível aplicativo de metas anuais para a sua empresa! Este aplicativo ajudará os colaboradores a preencherem suas metas anuais e auxiliará na avaliação de desempenho de cada colaborador e departamento.

## 📝 Sumário

- [Metas APP](#metas-app)
- [Descrição](#descrição)
- [Tecnologias](#tecnologias)
- [Instalação](#instalação)
- [Uso](#uso)
- [Contribuições](#contribuições)
- [Licença](#licença)
- [Contato](#contato)

## 📖 Descrição

**Metas APP** é uma aplicação web desenvolvida para facilitar o processo de preenchimento e acompanhamento das metas anuais dos colaboradores da empresa. Através desta aplicação, é possível realizar a avaliação de desempenho de cada colaborador e departamento, otimizando o gerenciamento e permitindo uma visão mais clara dos resultados alcançados.

## 🛠 Tecnologias

As seguintes tecnologias foram utilizadas no desenvolvimento deste projeto:

- CSS3
- JavaScript
- React
- Node.js
- Express
- MySQL

## ⚙ Instalação

### Pré-requisitos

Certifique-se de ter o Node.js e npm instalados.

## 🎮 Uso

Para utilizar o Metas APP, siga os passos abaixo:

1. Faça login com seu e-mail corporativo e a senha fornecida pela empresa.
![Login](https://user-images.githubusercontent.com/30526394/228895020-0f223d31-43e3-4229-99de-d4f61cc37af8.png)

2. Administradores terão acesso a todas as funcionalidades, como cadastrar colaboradores, ano francês, departamento etc.
![WelcomeAdmin](https://user-images.githubusercontent.com/30526394/228895043-55143220-3b26-42ad-9061-ab8be7d94031.png)

3. Responsáveis pelo departamento verão um atalho a mais na lateral esquerda chamado "METAS DO MEU TIME". Os demais colaboradores terão acesso às opções "MINHAS METAS" e "METAS DO DEPARTAMENTO".
![WelcomeResponsible](https://user-images.githubusercontent.com/30526394/228895521-88904fc9-d850-453b-b84d-489b30921e58.png)

4. Todos os colaboradores podem adicionar suas próprias metas. Porém, apenas o responsável pelo departamento pode criar metas do departamento.

5. Colaboradores do departamento podem apenas visualizar as metas do departamento.

### Regras e fluxos do app:

- Ao criar a meta individual, é necessário enviá-las para aprovação do superior.
- Há um fluxo de envio de e-mail ao final das etapas.
- Apenas o superior imediato pode criar/editar metas do departamento. Colaboradores podem visualizar.
- Metas só podem ser criadas/editadas/excluídas no período ativo do ano francês.
- Após a meta ser aprovada/salva e enviada, a meta original não pode ser alterada.
- Apenas o superior imediato pode preencher o resultado da meta.

### Passo a passo:

1. Após preencher as metas individuais, o colaborador deve clicar no botão "ENVIAR PARA VALIDAÇÃO" para enviar ao superior imediato.
![MetasIndividuais](https://user-images.githubusercontent.com/30526394/228895028-85002c1e-4b50-43a1-a986-b4623d8d0ba1.png)

2. O colaborador pode gerar um arquivo PDF das metas clicando no botão "GERAR PDF".
![PDFIndividualGoals](https://user-images.githubusercontent.com/30526394/228896408-6dd2bac0-b4ea-44cb-8558-3657f1b0f634.png)

3. Responsáveis pelo departamento, ao acessar "METAS DO MEU TIME", poderão visualizar as metas dos colaboradores do departamento e seus status.
![MetasdoMeuTime](https://user-images.githubusercontent.com/30526394/228895025-63d2fce2-b3ec-4dbe-b654-49832785a42d.png)

4. Ao clicar no botão "VISUALIZAR", o responsável poderá ver os detalhes da meta do colaborador.
![DetalhesMetasdoMeuTime](https://user-images.githubusercontent.com/30526394/228895013-474c9c65-5a3c-44ab-b4ac-021e594d5405.png)

5. Se necessário, o responsável pode clicar no botão "EDITAR" e alterar o status da meta para "EM PREENCHIMENTO" novamente, justificando o motivo. Depois, clicar em "ATUALIZAR".
![EditarMetasdoMeuTime](https://user-images.githubusercontent.com/30526394/228895017-8e1a2e30-c92f-46a3-ab14-23ec4a7746d2.png)

6. Para o colaborador, o status da meta não validada retorna para "EM PREENCHIMENTO" e um novo botão "MOTIVO DA RECUSA" aparece. Os botões "EDITAR" e "ENVIAR PARA VALIDAÇÃO" ficam disponíveis novamente.
![BotaoMotivoRecusa](https://user-images.githubusercontent.com/30526394/228895007-24197973-bb4f-44ea-8949-b6fff10cb0a6.png)

7. Ao clicar em "MOTIVO DA RECUSA", a mensagem do gestor com a justificativa aparecerá para o colaborador, que poderá ajustar a meta e reenviar para aprovação.
![VerMotivoRecusa](https://user-images.githubusercontent.com/30526394/228895041-3bae4d3f-0176-4e1c-b2df-417184c2666c.png)

8. Nas metas do departamento, também foi adicionada a opção de imprimir em PDF.
![MetasdoDepartamento](https://user-images.githubusercontent.com/30526394/228895021-7e72edb1-4a6d-42f4-8e7b-688ddc34b1cf.png)
![PDFDepartmentGoal](https://user-images.githubusercontent.com/30526394/228896399-8eddb6b2-e6e5-4351-9e1c-eb10fbb27f88.png)

9. Demais telas de cadastros para administradores.

Usuários:
![Users](https://user-images.githubusercontent.com/30526394/228895037-b05d37cb-7ffd-4e83-97a7-8af5819538ff.png)

Departamentos:
![Departamentos](https://user-images.githubusercontent.com/30526394/228895011-d1ccbedd-b667-476d-9dd0-bd11552ed6bc.png)

Responsáveis:
![Responsaveis](https://user-images.githubusercontent.com/30526394/228895032-0595e8be-ec4c-4da1-98ac-a22060b8158a.png)

Ano Francês:
![AnoFrances](https://user-images.githubusercontent.com/30526394/228894998-8a72de6e-1b45-4831-b86d-6f1d25f3cb4f.png)

Prontinho!
Agora você está pronto para usar o Metas APP e alcançar seus objetivos! 🚀


## 🤝 Contribuições

Em breve, aberto para contribuições que são super bem-vindas! 

## 📄 Licença

Este projeto está licenciado sob a Licença MIT. Consulte o arquivo `LICENSE` para obter detalhes.

## 📬 Contato

Mateus Furrier - matfurrier@gmail.com

Link do Projeto: [https://github.com/matfurrier/AppMetaNew](https://github.com/matfurrier/AppMetaNew)

Sinta-se à vontade para entrar em contato com qualquer dúvida, sugestão ou elogio. 
E não se esqueça de ⭐️ este projeto para ajudar a divulgá-lo! 😄


