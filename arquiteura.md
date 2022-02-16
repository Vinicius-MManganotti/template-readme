# Arquiteura - [Nome da Aplicação]

![Imagem do diagrama](https://user-images.githubusercontent.com/97189917/154343587-23692064-8b42-41b7-9fd7-850bd6a4ad4f.png)


```mermaid
flowchart LR
A[Github] -->|Novo commit| B(CircleCI)
B -->|Geração dos docs| C[Armazenamento GCP]
C -->|Renderização dos arquivos| D[Backstage]
