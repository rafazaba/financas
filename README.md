# 💰 Controle Financeiro

Aplicativo pessoal de controle financeiro — DRE, Balanço Patrimonial, provisão do carro (IPVA/Seguro/Revisão) e sync automático com Google Drive.

**👉 Acesse em qualquer dispositivo:** https://rafazaba.github.io/financas

---

## Como publicar / atualizar

1. Edite o arquivo `index.html` (ou `financas.html`) neste repositório
2. O GitHub Pages atualiza automaticamente em ~1 minuto

## Sync com Google Drive

- Abra o app pela URL acima (HTTPS obrigatório para o login funcionar)
- Clique no pill **"☁ Drive: clique para conectar"** no cabeçalho
- Faça login com sua conta Google no popup que aparecer
- Pronto — o app salva automaticamente no Drive após cada alteração

O arquivo salvo no Drive se chama `financas_sync.json`.  
O token de acesso dura ~1 hora; o app renova silenciosamente enquanto a aba estiver aberta.

## Estrutura

```
financas/
├── index.html    ← o app completo (single-file)
├── .nojekyll     ← desativa o processamento Jekyll do GitHub Pages
└── README.md     ← este arquivo
```
