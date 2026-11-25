# Resenha crítica: o FBI, o Sentinel e o Scrum

> Desafio de Projeto da DIO: resenha crítica sobre um case de sucesso com Scrum.
> Case escolhido: **Sentinel**, o sistema de gestão de casos do FBI (2006–2012).

## Ficha do case

| Item | Dado |
|------|------|
| Organização | FBI (Federal Bureau of Investigation), EUA |
| Projeto | Sentinel, sistema eletrônico de gestão de casos e informações investigativas |
| Antecessor fracassado | Virtual Case File (VCF), abandonado em abril de 2005 depois de cerca de US$ 170 milhões |
| Orçamento original do Sentinel | US$ 425 milhões, com entrega prevista para dezembro de 2009 |
| Virada para o ágil | setembro de 2010, com o desenvolvimento trazido para dentro do FBI |
| Entrega | em uso por todo o FBI desde 1º de julho de 2012 |
| Orçamento final | dentro do teto revisado de US$ 451 milhões, sem contar operação e manutenção |

## Resumo do case

O FBI passou mais de uma década tentando substituir o seu sistema de casos dos anos 1990, que dependia de papel e de telas antigas. A primeira tentativa, o Virtual Case File, foi contratada no modelo tradicional, com escopo fechado e entrega única. O resultado foram centenas de milhares de linhas de código que não serviam para o trabalho dos agentes, e o projeto foi cancelado em 2005.

O Sentinel começou em 2006 com uma grande contratada, a Lockheed Martin, ainda em modelo cascata e dividido em quatro fases. Em 2010, com cerca de US$ 405 milhões gastos e só as duas primeiras fases entregues, o FBI mandou parar o contrato.

O novo CIO, Chad Fulgham, e o CTO, Jeff Johnson, vinham do mercado financeiro. Eles levaram o projeto para dentro de casa e passaram a usar Scrum:

- o escopo restante virou um backlog de cerca de **670 histórias de usuário**;
- um **Product Owner** priorizava o que entrava em cada ciclo;
- as **sprints duravam duas semanas**, com **demonstração a cada sprint** para agentes e gestores;
- a equipe foi enxugada: a da Lockheed Martin caiu de cerca de 135 para 10 pessoas, e o projeto passou a ter cerca de 55 posições entre servidores e contratados;
- o orçamento de desenvolvimento para terminar o sistema foi de **US$ 32,6 milhões**.

Em julho de 2012, o Sentinel entrou em produção para todos os funcionários do FBI. Em 2014, a auditoria do OIG concluiu que a maioria dos usuários o usava todo dia e via impacto positivo no trabalho.

## Análise crítica

### O que o Scrum realmente resolveu

**1. Trocou promessa por software funcionando.** No VCF e na fase Lockheed, o progresso era medido em documentos e marcos contratuais. Com sprints de duas semanas e demonstrações frequentes, o progresso passou a ser medido no que os agentes conseguiam usar. Esse é o coração do Scrum: o incremento pronto é a única medida honesta de avanço.

**2. Aproximou quem usa de quem constrói.** O protótipo que guiou a retomada foi idealizado por agentes do próprio FBI, e as demos traziam usuários para dentro do ciclo. O VCF fracassou justamente por construir algo que ninguém tinha validado com quem ia usar.

**3. Deu um dono para a prioridade.** Com um Product Owner decidindo a ordem do backlog, as decisões deixaram de depender de aditivos contratuais e comitês. Segundo Johnson, o ganho principal foi dar poder de decisão rápida a quem estava perto do problema.

**4. Times menores, custo por ciclo menor.** Reduzir a equipe e trabalhar em ciclos curtos derrubou o ritmo de gasto. O OIG reconheceu que o FBI passou a gastar menos por mês e a acompanhar o projeto de forma mais direta.

### Onde a narrativa de sucesso exagera

**1. A conta dos "90% de economia" não fecha como costuma ser contada.** O case circula como "o FBI terminou com 10% do orçamento o que estava atrasado havia 10 anos". Os US$ 32,6 milhões do ágil vieram **depois** de cerca de US$ 405 milhões já gastos, e o Scrum herdou as fases 1 e 2 prontas, além da infraestrutura. O custo total do Sentinel ficou perto dos US$ 451 milhões. Na época, a imprensa especializada também noticiou que os custos de operação e manutenção, estimados em US$ 60 milhões, ficaram de fora dessa conta. O Scrum salvou a reta final, e não o projeto inteiro com um décimo do dinheiro.

**2. O prazo ágil também escorregou.** A meta inicial com Scrum era setembro de 2011. A entrega passou para dezembro, depois fevereiro, depois maio e, por fim, julho de 2012. Em agosto de 2011, segundo o OIG, havia cerca de 50% da funcionalidade planejada com 88% do cronograma consumido. Ágil não elimina atraso: ele torna o atraso visível mais cedo, o que é diferente.

**3. Era um "Scrum adaptado", com desvios importantes.** Uma análise da época apontou times de desenvolvimento e de teste com cerca de 25 pessoas cada, um único Scrum Master e equipes separadas em locais diferentes. O Scrum recomenda times pequenos e multifuncionais. O OIG também registrou que itens foram marcados como concluídos **antes do fim dos testes**, e que não havia registro de que cada sprint cumpria a Definition of Done. Sem uma Definition of Done respeitada, a velocidade do time é, em parte, ilusão.

**4. Parte do escopo foi adiada, e o produto chegou com lacunas.** Funcionalidades como relatórios, indexação de documentos e gestão de evidências foram empurradas para a última versão, e a migração de dados do sistema antigo foi reduzida. Dois anos depois da entrega, só 42% dos funcionários ouvidos pelo OIG disseram encontrar com frequência o que procuravam na busca. Priorizar é legítimo e faz parte do Scrum, mas o case de sucesso raramente conta o que ficou para trás.

**5. Quanto disso é Scrum e quanto é liderança?** A virada coincidiu com outras mudanças fortes: um CIO com respaldo direto do diretor do FBI, o fim da dependência de uma grande contratada, uma equipe interna menor e mais técnica, e uma base de código e de aprendizado de seis anos de tentativas anteriores. É impossível isolar o efeito do framework. O Scrum foi o veículo, mas a decisão de assumir o projeto e a autonomia dada ao time pesaram tanto quanto ele.

## Conclusão

O Sentinel é um bom case de Scrum, mas pelo motivo menos citado. Ele não prova que o ágil faz projetos custarem 10% do valor. Prova que ciclos curtos, um dono claro da prioridade e entregas validadas por usuários reais conseguem tirar do buraco um projeto que contratos rígidos e planejamento antecipado tinham afundado duas vezes.

As fraquezas do case também ensinam: uma Definition of Done ignorada, times grandes demais e escopo adiado sem transparência continuam sendo problemas, com ou sem sprints. Ler o case com os relatórios de auditoria ao lado, e não só com o material de divulgação, mostra um Scrum mais realista: menos milagre e mais disciplina.

## O que eu levo para a minha prática

- **Medir progresso pelo que está pronto e testado**, e não pelo que foi "começado" na sprint.
- **Levar o usuário para a demo.** O fracasso do VCF foi, antes de tudo, um fracasso de feedback.
- **Desconfiar de números redondos em cases de sucesso** e procurar a fonte primária (auditoria, relatório oficial) antes de repetir.
- **Adaptar o framework sem quebrar os pilares.** Ajustar cerimônias é aceitável. Abrir mão da Definition of Done e de times pequenos cobra o preço depois.

## Referências

- U.S. Department of Justice, Office of the Inspector General. *Interim Report on the FBI's Implementation of the Sentinel Project*, Audit Report 12-08, dez. 2011. <https://www.oversight.gov/sites/default/files/oig-reports/a1208.pdf>
- U.S. Department of Justice, Office of the Inspector General. *Interim Report on the FBI's Implementation of the Sentinel Project*, Audit Report 12-38, set. 2012. <https://www.oversight.gov/sites/default/files/oig-reports/a1238.pdf>
- U.S. Department of Justice, Office of the Inspector General. *Audit of the Status of the FBI's Sentinel Program*, Audit Report 14-31, set. 2014. <https://www.oversight.gov/sites/default/files/oig-reports/a1431.pdf>
- Goldstein, H. *Who Killed the Virtual Case File?* IEEE Spectrum, set. 2005. <https://spectrum.ieee.org/who-killed-the-virtual-case-file>
- *FBI's Sentinel Project: 5 Lessons Learned*. InformationWeek, ago. 2012. <https://www.informationweek.com/government/fbi-s-sentinel-project-5-lessons-learned>
- *FBI Sentinel Case Management System Actually Over Budget*. InformationWeek. <https://informationweek.com/it-sectors/fbi-sentinel-case-management-system-actually-over-budget>
- *How the FBI Proves Agile Works for Government Agencies*. CIO. <https://www.cio.com/article/2392970/how-the-fbi-proves-agile-works-for-government-agencies.html>
- *Report cites FBI's 'weaknesses' on Agile development*. Route Fifty, jan. 2011. <https://route-fifty.com/emerging-tech/2011/01/report-cites-fbis-weaknesses-on-agile-development/283690>
- *In Sentinel, the FBI finds an unlikely poster child for agile*. Nextgov, nov. 2015. <https://www.nextgov.com/modernization/2015/11/in-sentinel-the-fbi-finds-an-unlikely-poster-child-for-agile/207945/>
- Material de apoio do desafio: *Scrum Case: Como o FBI desenvolveu em 1 ano um projeto que estava atrasado há 10 anos*, Zappts Blog.
