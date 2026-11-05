# Skill `replica` (réplica trabalhista / impugnação à contestação)

Skill para Claude (formato `SKILL.md`) que conduz a elaboração de réplica no padrão PAB Advogados:
varredura dos autos, conferência da jurisprudência da ré, impugnação específica, módulo motorista e entrega no timbrado.

## Estrutura
```
skills/replica/SKILL.md
```

## Como adaptar
1. Copie `skills/replica` para `.claude/skills/` do projeto (ou envie como skill no Claude web).
2. Troque: persona/advogada, OAB, local de assinatura, endereço do timbrado, formatação (fonte, recuo).
3. Ajuste o caminho de saída (o original cita `/mnt/user-data/outputs/` e `present_files`, do Claude web).
4. Revise o arsenal jurídico e o módulo motorista conforme a área do escritório.
