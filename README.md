# Régis Pessolano

**Infraestrutura • Linux • Suporte N2/N3 • Automação • PowerShell**

Profissional de tecnologia com foco em administração de sistemas, diagnóstico técnico e automação de tarefas operacionais. Este perfil reúne soluções práticas, documentação de troubleshooting e scripts voltados a ambientes Windows e Linux.

## Áreas de atuação

- Infraestrutura e administração de sistemas
- Linux e Windows
- Suporte técnico N2/N3 e análise de causa raiz
- Automação com PowerShell e shell script
- Manutenção, desempenho e confiabilidade de estações de trabalho
- Documentação técnica e procedimentos reversíveis

## Projetos em destaque

### [Intel UHD 620 Driver Guard](https://github.com/RegisPessolano/intel-uhd620-driver-guard)

Guard em PowerShell que impede o Windows Update de substituir um driver Intel UHD Graphics 620 mais recente por pacotes antigos. Inclui detecção de versão, bloqueio dinâmico de downgrades, verificações sucessivas e proteção agendada.

### [Windows Maintenance Scripts](https://github.com/RegisPessolano/windows-maintenance-scripts)

Coleção documentada de scripts administrativos para diagnóstico e manutenção do Windows, com atenção a impacto, backup e reversão.

Entre os fluxos disponíveis está o [WSL1 com Debian para ambientes que utilizam undervolt](https://github.com/RegisPessolano/windows-maintenance-scripts/tree/main/scripts/wsl1-debian-undervolt), configurado para evitar conflitos com Hyper-V/VMP e ThrottleStop.

### [MPV para AMD C-50 / Radeon HD 6250](https://github.com/RegisPessolano/mpv-amd-c50-performance)

Configuração de desempenho do MPV para hardware legado em Linux, priorizando VA-API, filtros leves, fallback por software e uso controlado de memória.

### [Technical Casebook](https://github.com/RegisPessolano/technical-casebook)

Estudos de caso técnicos com investigação, evidências sanitizadas, correção, validação e lições aprendidas.

Primeiro caso: [FortiClient IPsec/IKEv2 e interferência de adaptador loopback na seleção do IP de origem](https://github.com/RegisPessolano/technical-casebook/blob/main/cases/networking/forticlient-ikev2-loopback.md). O diagnóstico mostrou como um adaptador virtual de terceiros pode interferir na escolha do endereço de origem da VPN. O funcionamento foi confirmado após reinicialização e desativação do adaptador, com distinção entre fatos observados e hipóteses.

## Em foco atualmente

- Automação segura de rotinas administrativas
- Troubleshooting reproduzível e bem documentado
- Compatibilidade entre hardware legado, drivers e sistemas atuais
- Ferramentas com validação, logs e caminhos claros de reversão

---

Os projetos deste perfil partem de problemas reais e priorizam documentação, previsibilidade e manutenção.
