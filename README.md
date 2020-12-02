## Deploy Contínuo
Nessa fase, o objetivo principal será fazer o deploy automático da aplicação já desenvolvida em Go Lang nas fases passadas.
As regras do processo são:
- Quando qualquer push ou uma PR for relizada no Github em um branch diferente do Master, o processo de CI tem que ser executado.
- Quando um merge ou um push entrarem no branch Master, o processo de CI/CD deve ser chamado, fazendo assim o deploy de forma automática no Kubernetes.

URL: http://34.72.22.194/