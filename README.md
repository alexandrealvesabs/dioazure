# dioazure
🚀 Monitoramento de Máquinas Virtuais no Azure
Este repositório faz parte do desafio da plataforma DIO com o objetivo de aplicar, na prática, o monitoramento de recursos no Microsoft Azure, com foco em Máquinas Virtuais (VMs).

📘 Objetivo do Projeto
Demonstrar como configurar e gerenciar o monitoramento de VMs na nuvem Azure, garantindo:

Visibilidade sobre o desempenho da máquina.

Controle e auditoria de eventos críticos (exclusão, paradas inesperadas, etc.).

Respostas proativas a incidentes via alertas.

🧰 Tecnologias e Ferramentas Utilizadas
Microsoft Azure Portal

Azure Monitor

Log Analytics

Alertas de Métricas

Azure Activity Log

Git e GitHub

Markdown

✅ Etapas Realizadas
Criação da Máquina Virtual (VM)

Nome: vm-monitoramento

Sistema operacional: Windows/Linux

Configuração de recursos padrão

Habilitação do Monitoramento

Ativação da coleta de diagnósticos

Associação com um workspace do Log Analytics

Criação de Alertas

Alerta para evento de exclusão de VM

Alerta para uso elevado de CPU (> 80%)

Configuração de ação por e-mail

Validação e Testes

Simulação de exclusão da VM

Monitoramento dos logs gerados no Activity Log

Verificação da recepção do alerta

📄 Capturas de Tela
As imagens estão organizadas na pasta /images, incluindo:

Configuração de diagnósticos

Criação de alertas

Alertas recebidos por e-mail

Painel do Azure Monitor

💡 Dicas Importantes
Sempre associe a VM a um Log Analytics Workspace antes de configurar alertas personalizados.

Os diagnósticos de boot ajudam a entender falhas no provisionamento da VM.

Utilize o Azure Activity Log para rastrear ações administrativas como exclusão de recursos.

Recomenda-se criar ações de grupo para reaproveitar notificações em diferentes alertas.

📚 Referências e Recursos
Documentação Oficial - Monitoramento de VMs no Azure

GitHub Markdown Cheatsheet

Curso DIO: Fundamentos do Azure

