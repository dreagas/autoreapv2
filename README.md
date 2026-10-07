<div align="center">

# AutoREAP

### Assistente desktop para automatizar etapas repetitivas do preenchimento de declarações REAP

**Windows • Python • PySide6 / Qt • Selenium**

[Baixar versão mais recente](https://github.com/dreagas/autoreapv2/releases) · [Ver releases](https://github.com/dreagas/autoreapv2/releases)

</div>

---

## Sobre o AutoREAP

O **AutoREAP** é um aplicativo para Windows criado para auxiliar no preenchimento de declarações **REAP** no portal **PesqBrasil**.

A proposta é reduzir tarefas repetitivas durante o processo de preenchimento. O usuário seleciona o **ano**, os **meses** desejados e configura as informações relacionadas à sua atividade; a partir disso, o AutoREAP automatiza as etapas correspondentes no navegador.

O aplicativo funciona como um **assistente de preenchimento**. A autenticação no portal continua sendo realizada pelo próprio usuário e os dados devem ser revisados antes da conclusão ou envio da declaração.

---

## Principais recursos

- Automação de etapas repetitivas do preenchimento REAP;
- Seleção de ano e meses para processamento;
- Configuração das informações da atividade;
- Acompanhamento do andamento da automação;
- Possibilidade de interromper o processo;
- Repetição de determinadas etapas quando necessário;
- Perfis de configuração;
- Simulação do preenchimento antes da execução;
- Ferramentas para download de documentos;
- Regras específicas de preenchimento por ano;
- Sistema de licenciamento;
- Modo gratuito com limites locais;
- Registro das execuções;
- Mecanismo de atualização do aplicativo;
- Testes automatizados para partes do sistema.

---

## Como funciona

O fluxo geral é simples:

1. Abra o AutoREAP;
2. Configure ou selecione um perfil;
3. Escolha o ano e os meses desejados;
4. Informe os dados referentes à atividade;
5. Inicie o processo;
6. Faça login e autentique-se no portal quando solicitado;
7. Acompanhe a automação pelo aplicativo;
8. Revise cuidadosamente os dados preenchidos antes de concluir ou enviar a declaração.

Durante a execução, o usuário pode acompanhar o progresso e interromper a automação quando necessário.

---

## Importante

> **O AutoREAP não substitui a conferência do usuário.**

O aplicativo automatiza etapas de preenchimento, mas a responsabilidade de revisar os dados antes da conclusão ou envio da declaração permanece com o usuário.

Alterações no portal, regras de preenchimento ou particularidades de uma declaração podem exigir conferência manual.

---

## Tecnologias

O AutoREAP é desenvolvido como uma aplicação desktop em Python.

| Área | Tecnologia |
|---|---|
| Linguagem | Python |
| Interface gráfica | PySide6 / Qt |
| Automação do navegador | Selenium |
| Plataforma principal | Windows |
| Configurações | Serviços internos de configuração e perfis |
| Licenciamento | Sistema próprio de licenças |
| Atualizações | Serviço de atualização do aplicativo |
| Downloads | Serviço dedicado para documentos |
| Registros | Logs de execução |
| Qualidade | Testes automatizados |

---

## Arquitetura

O projeto é dividido em serviços responsáveis por diferentes partes da aplicação, incluindo:

- interface desktop;
- automação do navegador;
- gerenciamento de configurações;
- perfis do usuário;
- licenciamento;
- atualizações;
- downloads;
- registros de execução;
- regras específicas por período;
- testes automatizados.

Essa separação permite que recursos como automação, configuração e atualização evoluam de forma independente.

---

## Download

As versões públicas do AutoREAP são distribuídas pela página de **Releases** deste repositório.

### [Baixar AutoREAP](https://github.com/dreagas/autoreapv2/releases)

Recomenda-se utilizar sempre a versão mais recente disponível.

---

## Código-fonte

O código-fonte principal do AutoREAP é mantido em repositório privado.

Este repositório público é utilizado principalmente para disponibilização de versões, informações do projeto e downloads oficiais das releases.

---

## Status do projeto

O AutoREAP está em desenvolvimento contínuo.

Novas versões podem incluir:

- correções de compatibilidade;
- ajustes para mudanças no fluxo do portal;
- melhorias de interface;
- novas validações;
- aprimoramentos de estabilidade;
- atualizações nas regras específicas de preenchimento.

---

## Aviso de uso

Automação de navegador depende da estrutura e do comportamento do sistema acessado. Mudanças realizadas no portal podem exigir atualizações no AutoREAP.

Sempre confira as informações preenchidas antes de concluir qualquer operação.

---

<div align="center">

Desenvolvido por **André Agas**

[GitHub](https://github.com/dreagas)

</div>
