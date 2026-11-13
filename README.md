# PLAYER SYSTEM — PHYSICAL EVOLUTION 2.0

## Conteúdo
- `index.html`: aplicativo funcional.
- `manifest.webmanifest`: metadados de instalação PWA.
- `sw.js`: cache offline/service worker.
- `icon.svg`: ícone do aplicativo.

## Recursos implementados
- Nível, EXP e progressão automática.
- Atributos: força, resistência, mobilidade, disciplina e intelecto.
- Missões diárias e semanais.
- Plano de treino de 5 dias, sem equipamentos.
- Cronômetro de descanso.
- Histórico local de ações.
- Conquistas, classe e habilidades.
- Salvamento automático no armazenamento local do navegador.
- Exportar/importar backup JSON.
- PWA com cache offline.

## Publicar para obter um link público
O PWA precisa ser servido por HTTPS (ou localhost). Faça upload de todos os arquivos para um repositório GitHub e ative GitHub Pages em Settings > Pages > Deploy from a branch > main > /(root). O endereço público será exibido pelo GitHub Pages. Depois, abra esse endereço no Chrome do Android e escolha "Instalar app" ou "Adicionar à tela inicial".

## Importante sobre os dados
Esta versão salva os dados neste navegador/dispositivo. Limpar os dados do navegador pode apagá-los. Use Exportar backup regularmente. Sincronização em nuvem entre aparelhos ainda não está implementada.

## Segurança do treino
O aplicativo é um organizador, não um diagnóstico ou supervisão profissional. Faça aquecimento, adapte repetições à sua capacidade e interrompa se houver dor aguda, tontura ou mal-estar. Não é necessário treinar até a falha.
