# ✈️ Consulta de Voos

Aplicação web para pesquisar passagens aéreas nacionais e internacionais,
comparando preços em dinheiro e pontos/milhas entre LATAM, Azul, Smiles e GOL.

## 🚀 Deploy

Apenas abra o `index.html` no navegador ou faça deploy no **GitHub Pages**:

1. Faça upload deste repositório
2. Ative GitHub Pages em Settings → Pages → branch `main`
3. Pronto!

## 🔑 Configuração

1. Obtenha uma chave da [GeckoAPI](https://geckoapi.com.br)
2. Cole no campo "Chave GeckoAPI" no topo da página
3. Clique em 💾 para salvar (fica no `localStorage`)

## 🎯 Funcionalidades

- 🇧🇷 Nacional e 🌎 Internacional
- 🔄 Ida/Volta ou ➡️ Apenas Ida
- 💰 Dinheiro, 🎯 Pontos, ou Ambos
- ✈️ Exibe a cia **operadora** real de cada voo
- 📊 Tabela de tarifas por voo
- 💬 Compartilhar cotação via WhatsApp
- 🐛 Modo Debug para diagnóstico

### CIAs suportadas

| Cia | Dinheiro | Pontos | API GeckoAPI |
|-----|----------|--------|--------------|
| LATAM | ✅ | ✅ (LATAM Pass) | `latamairlines.com` |
| Azul | ✅ | ✅ (TudoAzul) | `voeazul.com.br` |
| Smiles | ❌ | ✅ (SMILES / Club) | `smiles.com.br` |
| GOL | ✅ | ❌ | `voegol.com.br` |

## 🏗️ Estrutura do Código

