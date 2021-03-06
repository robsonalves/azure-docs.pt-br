# Visão geral
## [O que é a Automação do Azure?](automation-intro.md)
# Introdução
## [Introdução à Automação do Azure](automation-offering-get-started.md)
## Tutorial de runbook
### [Criar runbook gráfico](automation-first-runbook-graphical.md)
### [Criar runbook do PowerShell](automation-first-runbook-textual-powershell.md)
### [Meu primeiro runbook do Python](automation-first-runbook-textual-python2.md)
### [Criar runbook de Fluxo de Trabalho do PowerShell](automation-first-runbook-textual.md)
# Como
## Autenticação e segurança
### [Criar conta de Automação autônoma](automation-create-standalone-account.md)
### [Criar conta de Usuário do Azure AD](automation-create-aduser-account.md)
### [Configurar Autenticação com o AWS](automation-config-aws-account.md)
### [Criar Conta de automação Executar como](automation-create-runas-account.md)
### [Validar a configuração da conta de Automação](automation-verify-runas-authentication.md)
### [Gerenciar controle de acesso baseado em função](automation-role-based-access-control.md)
### [Gerenciar conta de Automação](automation-manage-account.md)
## Criar runbooks
### [Tipos de runbook](automation-runbook-types.md)
### [Criar e importar runbooks](automation-creating-importing-runbook.md)
### [Editar runbooks textuais](automation-edit-textual-runbook.md)
### [Editar runbooks gráficos](automation-graphical-authoring-intro.md)
### [Testar um runbook](automation-testing-runbook.md)
### [Aprender o fluxo de trabalho do PowerShell](automation-powershell-workflow.md)
### [Runbooks filhos](automation-child-runbooks.md)
### [Saída de runbook](automation-runbook-output-and-messages.md)
### [Integração de controle de origem](automation-source-control-integration.md)
## Automatizar
### [Iniciar um runbook](automation-starting-a-runbook.md)
### [Iniciar runbook a partir de um webhook](automation-webhooks.md)
### [Configurar parâmetros de entrada do Runbook](automation-runbook-input-parameters.md)
### [Tratamento de erros nos runbooks gráficos](automation-runbook-graphical-error-handling.md)
### [Controlar um trabalho de runbook](automation-runbook-execution.md)
### [Alterar configurações de runbook](automation-runbook-settings.md)
### [Gerenciar dados da Automação do Azure](automation-managing-data.md)
### [Chamar Runbook de Automação do Azure a partir do alerta do Log Analytics](automation-invoke-runbook-from-omsla-alert.md)
### [Passar um objeto JSON para um runbook de Automação do Azure](automation-pass-json-string.md)
## Hybrid Runbook Worker
### [Implantar Hybrid Runbook Worker](automation-hybrid-runbook-worker.md)
### [Hybrid Runbook Worker Windows da Automação do Azure](automation-windows-hrw-install.md)
### [Hybrid Runbook Worker Linux da Automação do Azure](automation-linux-hrw-install.md)
### [Executar runbooks no trabalho](automation-hrw-run-runbooks.md)
### [Remover Runbook Workers Híbridos da Automação do Azure](automation-remove-hrw.md)
## Implantar gerenciamento de configuração (DSC)
### [Visão geral da Configuração do Estado Desejado (DSC)](automation-dsc-overview.md)
### [Guia de Introdução](automation-dsc-getting-started.md)
### [Configurar servidores para um estado desejado e gerenciar descompasso na Automação do Azure](tutorial-configure-servers-desired-state.md)
### [Integração de computadores para gerenciamento](automation-dsc-onboarding.md)
### [Compilação de configurações DSC](automation-dsc-compile.md)
### [Implantação contínua usando Chocolatey](automation-dsc-cd-chocolatey.md)
### [Encaminhar dados de relatório DSC de Automação do Azure para o OMS Log Analytics](automation-dsc-diagnostics.md)
## Gerenciar ativos
### [Certificados](automation-certificates.md)
### [Conexões](automation-connections.md)
### [Credenciais](automation-credentials.md)
### [Módulos de Integração](automation-integration-modules.md)
### [Agendas](automation-schedules.md)
### [Variáveis](automation-variables.md)
### [Atualizar os módulos do Azure PowerShell](automation-update-azure-modules.md)
## Cenários
### [Galeria de Runbook](automation-runbook-gallery.md)
### [Criar VM do Amazon Web Service](automation-scenario-aws-deployment.md)
### [Corrigir alerta da VM do Azure](automation-azure-vm-alert-integration.md)
### [Iniciar/parar VM com marcações JSON](automation-scenario-start-stop-vm-wjson-tags.md)
### [Remover grupo de recursos](automation-scenario-remove-resourcegroup.md)
### [Integração de controle do código-fonte com o GitHub Enterprise](automation-scenario-source-control-integration-with-github-ent.md)
### [Integração de controle do código-fonte com o VSTS](automation-scenario-source-control-integration-with-VSTS.md)
### [Chamar Runbook de Automação do Azure a partir do alerta do Log Analytics](automation-invoke-runbook-from-omsla-alert.md)
### [Implantar um modelo do Azure Resource Manager em um runbook do PowerShell de Automação do Azure](automation-deploy-template-runbook.md)
## Soluções
### [Gerenciamento de atualizações](../operations-management-suite/oms-solution-update-management.md)
#### [Gerenciar atualizações de várias VMs](manage-update-multi.md)
#### [Integrar SCCMr com o gerenciamento de atualizações do OMS](oms-solution-updatemgmt-sccmintegration.md)
### [Controle de alterações](../log-analytics/log-analytics-change-tracking.md)
### [Controlar alterações em VMs](automation-vm-change-tracking.md)
### [Gerenciar uma VM com coleta de inventário](automation-vm-inventory.md)
### [Iniciar/parar VMs durante os horários inativos](automation-solution-vm-management.md)
## Monitoramento
### [Encaminhar dados de trabalho de Automação do Azure para o Log Analytics](automation-manage-send-joblogs-log-analytics.md)
### [Desvincular conta de Automação do Azure do Log Analytics](automation-unlink-from-log-analytics.md)
## Migrar
### [Migrar do Orchestrator](automation-orchestrator-migration.md)
### [Mover a Conta de Automação](automation-migrate-account-subscription.md)
## Solucionar problemas
### [Solucionar erros comuns](automation-troubleshooting-automation-errors.md)
### [Solucionar problemas do Hybrid Runbook Worker](automation-troubleshooting-hybrid-runbook-worker.md)
# Referência
## [PowerShell do Azure](/powershell/module/azurerm.automation)
## [Azure PowerShell (Clássico)](/powershell/module/azure/?view=azuresmps-3.7.0)
## [.NET](/dotnet/api/microsoft.azure.management.automation)
## [REST](/rest/api/automation)
## [REST (Clássico)](https://msdn.microsoft.com/library/azure/mt163781)
# Recursos
## [Vídeo de introdução à Automação](https://azure.microsoft.com/documentation/videos/azure-automation-101-with-powershell-and-eamon-o-reilly/)
## [Treinamento em Automação do Azure](https://mva.microsoft.com/en-US/training-courses/automating-the-cloud-with-azure-automation-8323?l=C6mIpCay_4804984382)
## [Roteiro do Azure](https://azure.microsoft.com/roadmap/?category=monitoring-management)
## [Roteiro de aprendizagem](https://azure.microsoft.com/documentation/learning-paths/automation/)
## [Fórum do MSDN](https://social.msdn.microsoft.com/Forums/azure/en-US/home?forum=azureautomation)  
## [Preços](https://azure.microsoft.com/pricing/details/automation/)  
## [Calculadora de preço](https://azure.microsoft.com/pricing/calculator/)
## [Notas de versão](https://azure.microsoft.com/updates/?product=automation)
## [Atualizações de serviço](https://azure.microsoft.com/updates/?product=automation)
## [Stack Overflow](http://stackoverflow.com/questions/tagged/azure-automation)
## [Vídeos](https://azure.microsoft.com/documentation/videos/index/?services=automation)
