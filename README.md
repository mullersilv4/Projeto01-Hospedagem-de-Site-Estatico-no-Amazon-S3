# Projeto01-Hospedagem-de-Site-Estatico-no-Amazon-S3

🎯 Objetivo:
Migrar um site estático para o Amazon S3, melhorando a confiabilidade e a disponibilidade da aplicação. Neste projeto, explorei conceitos básicos de computação em nuvem e armazenamento de objetos, utilizando políticas de bucket para controle de acesso.


🛠️ Serviços AWS Utilizados

Amazon S3 → Armazenamento dos arquivos do site e habilitação do recurso de Static Website Hosting.

Bucket Policy (IAM) → Configuração de permissões públicas para acesso aos arquivos do site.


🚀 Etapas Realizadas

Criação de um bucket no S3 com nome único e configuração da região.

Upload dos arquivos do site (HTML, CSS, JS, imagens).

Ativação da opção Static Website Hosting no bucket.

Definição do documento padrão (index.html).

Ajuste da bucket policy para permitir acesso público de leitura aos objetos.

Teste de acesso ao site pelo endpoint público gerado pelo S3.

📊 Resultado

O site estático ficou acessível via URL pública do S3.

Foi aplicada uma política de bucket garantindo que apenas leitura pública fosse permitida, protegendo contra alterações indevidas.

🔧 Próximos Passos (Evoluções Futuras)

Integrar Amazon CloudFront para distribuição de conteúdo global com baixa latência.

Configurar Route 53 para usar um domínio customizado.

Habilitar SSL/TLS com ACM para navegação segura (HTTPS).

![Diagrama](https://github.com/user-attachments/assets/dd4f5266-4840-4d98-b430-846f92bacfd3)
