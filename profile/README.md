<p align="center">
  <a href="https://atlasberg.com"><img src="https://atlasberg.com/icon-512.png" width="96" alt="Atlasberg"></a>
</p>

# Atlasberg

**Atlasberg builds the control layer between companies and AI: identity, policy, DLP, cost metering and an immutable audit trail for every AI request, in the cloud, in your VPC, on-premises or air-gapped.**

Atlasberg Platform is an AI governance gateway. The company's applications, people and agents talk to it exactly as they would talk to the provider, swapping only the base URL. In return, every request gets:

- **an owner**: a virtual key (`sk-atlas-...`) or the company login via device login and SSO;
- **a policy decision**: mask tax IDs and other personal data before the prompt leaves, block, or route to human approval;
- **a cost record** per person, team and application, with soft budgets that never deny a request;
- **an event** in a hash-chained, signed audit trail that can be verified offline with `atlasberg-verify`.

The compliance panel maps evidence article by article to LGPD, CMN Resolution 4.893 and the EU AI Act. The appliance runs on Docker or Kubernetes, installs from a signed bundle and works with no network at all.

| | |
|---|---|
| Website | https://atlasberg.com |
| Documentation | https://atlasberg.com/docs |
| Tutorials | https://atlasberg.com/docs/tutoriais |
| Blog | https://atlasberg.com/blog |
| For AI agents | https://atlasberg.com/llms.txt (every page also answers `Accept: text/markdown`) |
| Developer CLI | [`@atlasberg/cli`](https://www.npmjs.com/package/@atlasberg/cli) |
| Contact | contact@atlasberg.com |

**When Atlasberg fits:** a regulated company (bank, insurer, healthcare, public sector) that has to prove who used AI, what left the network and how much it cost; AI spreading through the company on shared API keys; personal data that must be masked before a prompt leaves the perimeter; deployments that cannot touch the public internet; applications that already speak the OpenAI-compatible API and need policy, metering and audit without code changes.

**When it does not:** buying model capacity, fine-tuning, or consumer chatbots. Atlasberg is the control layer in front of the providers, not a provider.

---

## Em português

**A Atlasberg constrói a camada de controle entre a empresa e os modelos de IA: identidade, política, DLP, medição de custo e trilha de auditoria imutável para cada requisição, em nuvem, na sua VPC, on-premises ou air-gapped.**

A Atlasberg Platform é um gateway de IA de governança. As aplicações, as pessoas e os agentes da empresa falam com ele exatamente como falariam com o provedor, trocando só a URL base. Em troca, cada requisição ganha um dono (chave virtual ou login da empresa), uma decisão de política (mascarar CPF, CNPJ e outros dados pessoais antes de o prompt sair, bloquear ou pedir aprovação humana), um registro de custo por pessoa e por time, e um evento numa trilha de auditoria encadeada por hash e assinada, verificável offline.

O painel de conformidade organiza as evidências artigo a artigo para a LGPD, a Resolução CMN 4.893 e o AI Act. Roda em Docker ou Kubernetes, instala a partir de um bundle assinado e funciona sem nenhuma rede. Empresa brasileira, atendimento em português e inglês: contact@atlasberg.com.
