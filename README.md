# Desafio Quality Assurance 2026.2 - Projeto NaSalinha

Bem-vindo ao repositório da auditoria de qualidade do projeto NaSalinha, desenvolvido no âmbito do desafio de QA da Comp JÚNIOR.

---

## Sobre o Projeto
O NaSalinha é a aplicação sob auditoria neste projeto. O objetivo desta iniciativa é realizar um processo completo de garantia de qualidade (QA), desde o planeamento de casos de testes até à execução de testes manuais, de interface, de API e de regressão, identificando e documentando falhas (bugs) no sistema.

---

## Tecnologias e Ferramentas

Neste projeto de QA são utilizadas as seguintes ferramentas:

* Gestão de Projeto & Documentação: GitHub (pasta /docs)
* Execução de Testes de API: Postman
* Virtualização de Ambiente: Docker 
* Navegadores para Testes Funcionais: Google Chrome

---

## Estratégia e Tipos de Testes

A auditoria foca-se nas 3 áreas Core do sistema:
1. Autenticação JWT: Gestão de acessos e permissões.
2. Check-in por Foto: Upload e validação de ficheiros de comunicação/mídia.
3. Sistema de Pontos: Cálculo, persistência de dados e atualização do ranking.

### Tipos de Testes Aplicados:
* Testes Funcionais (UI): Validação dos fluxos na interface do utilizador.
* Testes de API: Validação dos endpoints, regras de negócio e códigos de estado HTTP (200, 201, 400, 404, 500, etc.).
* Testes de Regressão: Simulação de fluxos após correções para garantir a estabilidade das funcionalidades existentes.

---

## Cronograma e Entregas por Semana

| Semana | Foco Principal | Entregas e Ações Previstas |
| :--- | :--- | :--- |
| **Semanas 1-2** | Setup, Exploração e Documentação | Subir ambiente em Docker; criar repositório no GitHub; explorar fluxos do utilizador; redigir o `README.md` inicial.|
| **Semana 3** | Planeamento e Design de Testes | Definir cenários para as 3 áreas Core; escrever Casos de Teste (positivos/negativos); configurar a ferramenta de gestão |
| **Semana 4** | Execução de Testes Manuais (UI) | Executar os casos de teste de interface planeados; registar |
| **Semana 5** | Testes de API e Integração | Validar endpoints e status codes no Insomnia/Postman; verificar regras de negócio no backend; registar bugs de API |
| **Semana 6** | Testes de Regressão e Re-teste | Re-testar bugs reportados; descrever a simulação do teste de regressão; refinar relatórios de bugs |
| **Semana 7** | Finalização, Revisão e Entrega | Revisão geral da documentação; gravação do vídeo de demonstração (máx. 10 min); disponibilizar repositório final. |

---

## Como Executar o Ambiente Local

### Pré-requisitos
* Git instalado.
* Docker Desktop instalado e em execução.

### Passos para subir a aplicação:

1. Clona o repositório original do projeto NaSalinha:
   ```bash
   git clone <URL_DO_REPOSITORIO_NASALINHA>
   cd NaSalinha
