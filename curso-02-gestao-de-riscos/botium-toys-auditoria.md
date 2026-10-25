# AUDITORIA DE SEGURANÇA DA INFORMAÇÃO
### Estudo de Caso: Botium Toys

**Área:** Cibersegurança | Segurança Defensiva | Análise de Riscos  
**Origem:** Google Cybersecurity Certificate  
**Tipo de projeto:** Atividade prática educacional  
**Empresa analisada:** Botium Toys (empresa fictícia)

## 1. Objetivo do projeto

O objetivo deste projeto foi analisar os controles de segurança da informação de uma empresa fictícia, identificar possíveis vulnerabilidades em seus processos e avaliar oportunidades de melhoria na proteção dos dados e dos ativos da organização.

A atividade teve como foco a análise de controles de acesso, proteção de dados, segurança física, disponibilidade das informações e práticas relacionadas à conformidade.

## 2. Contexto e escopo

A Botium Toys é uma empresa fictícia que comercializa brinquedos por meio de lojas físicas e de uma plataforma on-line, atendendo clientes de diferentes regiões do mundo.

O escopo do estudo abrangeu o programa de segurança da informação, os ativos da organização, os processos internos e os controles existentes.

De acordo com o relatório fornecido na atividade, a avaliação de risco da empresa recebeu pontuação 8 de 10, classificada como alta.

## 3. Metodologia

A análise foi realizada por meio da leitura e interpretação dos documentos fornecidos na atividade educacional.

As etapas incluíram:

1. Análise do escopo, dos objetivos e do relatório de avaliação de riscos.
2. Identificação dos controles de segurança existentes e ausentes.
3. Preenchimento da lista de verificação de controles.
4. Análise das práticas relacionadas ao PCI DSS, ao GDPR e aos controles SOC.
5. Identificação de riscos e elaboração de recomendações de melhoria.

A análise foi documental e baseada nas informações disponibilizadas no estudo de caso. Não foram realizados testes técnicos em sistemas reais.

## 4. Principais constatações

### 4.1. Controle de acesso

**Problema identificado:** o relatório informa que todos os funcionários possuem acesso aos dados armazenados internamente e podem acessar informações de cartões de pagamento e dados pessoais de clientes.

**Risco:** o acesso excessivo pode aumentar a possibilidade de exposição indevida de informações sensíveis.

**Recomendação:** implementar o princípio do menor privilégio, concedendo a cada funcionário apenas os acessos necessários para suas atividades.

### 4.2. Proteção e criptografia de dados

**Problema identificado:** o relatório informa que a empresa não utiliza criptografia para proteger as informações de cartões de crédito processadas e armazenadas localmente.

**Risco:** informações financeiras podem ficar mais expostas em caso de acesso não autorizado.

**Recomendação:** avaliar e implementar mecanismos adequados de criptografia para proteger os dados em trânsito e em repouso, conforme os requisitos aplicáveis.

### 4.3. Backup e recuperação de desastres

**Problema identificado:** a empresa não possui um plano de recuperação de desastres e não realiza backups dos dados críticos, segundo o relatório.

**Risco:** incidentes, falhas técnicas ou ataques cibernéticos podem resultar em perda de informações e interrupção das operações.

**Recomendação:** estabelecer uma estratégia de backup, testar a recuperação dos dados e desenvolver um plano de recuperação de desastres.

### 4.4. Monitoramento e detecção de ameaças

**Problema identificado:** o relatório informa que a empresa não possui um sistema de detecção de intrusões (IDS).

**Risco:** atividades suspeitas podem passar despercebidas, dependendo dos outros mecanismos de monitoramento existentes.

**Recomendação:** avaliar a implementação de mecanismos de detecção e monitoramento de eventos de segurança, considerando as necessidades e os recursos da organização.

### 4.5. Gerenciamento de senhas

**Problema identificado:** a empresa possui uma política de senhas, mas ela não atende adequadamente aos padrões modernos de complexidade. Também não possui um gerenciador centralizado de senhas.

**Risco:** práticas inadequadas de autenticação podem aumentar a exposição a ataques relacionados a credenciais.

**Recomendação:** revisar a política de autenticação, adotar práticas seguras de gerenciamento de credenciais e avaliar a implementação de autenticação multifator.

### 4.6. Sistemas legados

**Problema identificado:** os sistemas legados são monitorados e mantidos, mas não existe um cronograma regular claramente definido, e os procedimentos de intervenção não estão claros.

**Risco:** a manutenção irregular pode dificultar a identificação de problemas e a redução de vulnerabilidades.

**Recomendação:** documentar os procedimentos de manutenção, estabelecer um cronograma e acompanhar a aplicação de atualizações de segurança.

## 5. Controles de segurança existentes

O relatório também identifica controles já presentes na organização:

- Firewall com regras de filtragem de tráfego.
- Software antivírus instalado e monitorado.
- Fechaduras nas instalações físicas.
- Sistema de câmeras de vigilância atualizado.
- Sistemas de detecção e prevenção de incêndios.
- Controles destinados a preservar a integridade dos dados.
- Plano para notificar clientes da União Europeia sobre violações de dados em até 72 horas.
- Políticas e processos de privacidade desenvolvidos e aplicados.

A existência desses controles é positiva, mas não elimina os riscos associados às deficiências identificadas.

## 6. Prioridades de melhoria

Com base nas constatações do estudo de caso, as seguintes ações merecem atenção:

**Prioridade alta**
- Restringir o acesso a dados pessoais e financeiros.
- Melhorar a proteção dos dados de cartões de pagamento.
- Estabelecer backups dos dados críticos e um plano de recuperação.
- Revisar as práticas de gerenciamento de senhas.

**Próximas etapas**
- Avaliar mecanismos de detecção de intrusões.
- Formalizar a manutenção dos sistemas legados.
- Revisar a separação de funções.
- Verificar os procedimentos de classificação e inventário dos dados.

Essas prioridades são recomendações preliminares baseadas no relatório, e não o resultado de testes técnicos independentes.

## 7. Aprendizados

A realização desta atividade contribuiu para o desenvolvimento de conhecimentos introdutórios em:

- Identificação e análise de riscos de segurança.
- Avaliação de controles de segurança da informação.
- Princípio do menor privilégio.
- Proteção de dados pessoais e financeiros.
- Importância de backups e recuperação de desastres.
- Fundamentos de monitoramento e detecção de ameaças.
- Análise documental de práticas de conformidade.
- Elaboração de recomendações para redução de riscos.

## 8. Limitações

Este projeto utiliza uma empresa fictícia e informações fornecidas em uma atividade educacional.

Não foram realizados testes de invasão, varreduras de vulnerabilidades, análise de tráfego de rede ou validações técnicas em ambientes reais.

As constatações e recomendações estão limitadas às informações disponibilizadas no estudo de caso.

## 9. Conclusão

O estudo de caso demonstrou a importância de avaliar os controles de segurança de forma integrada, considerando confidencialidade, integridade e disponibilidade das informações.

A análise permitiu identificar deficiências relacionadas ao controle de acesso, à criptografia, aos backups, ao gerenciamento de senhas e à detecção de ameaças.

A atividade reforçou a importância de analisar evidências, documentar riscos e recomendar melhorias de segurança de acordo com as necessidades da organização.

**Status do projeto:** estudo de caso educacional em desenvolvimento.
