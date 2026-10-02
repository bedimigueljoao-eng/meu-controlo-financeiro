# Meu Controlo Financeiro - PWA

Aplicacao instalavel para Android, responsiva e offline. Controla dinheiro pessoal por subcontas, dividas, dinheiro de terceiros, emprestimos e locais criados pelo utilizador.

## Publicar no GitHub Pages

1. Crie um repositorio no GitHub, por exemplo `meu-controlo-financeiro`.
2. Envie **todos** os ficheiros e pastas deste pacote para a raiz do repositorio.
3. Abra `Settings > Pages`.
4. Em `Build and deployment`, selecione `GitHub Actions`.
5. Abra o separador `Actions` e aguarde o workflow `Deploy PWA to GitHub Pages` terminar.
6. O endereco sera semelhante a `https://SEU-USUARIO.github.io/meu-controlo-financeiro/`.

Nao e necessario instalar programas no computador. Os ficheiros podem ser enviados pela interface web do GitHub.

## Instalar no Android

1. Abra o endereco publicado no Google Chrome.
2. Aguarde alguns segundos e toque em `Instalar aplicacao` quando o botao aparecer.
3. Se o botao nao aparecer, abra o menu do Chrome e escolha `Instalar aplicacao` ou `Adicionar ao ecra principal`.

## Dados e funcionamento offline

- Depois do primeiro acesso, a aplicacao abre sem internet.
- Os dados ficam guardados no dispositivo e navegador em que foram criados.
- Use `Exportar backup` regularmente.
- Para mudar de aparelho, exporte o backup no aparelho antigo e use `Importar backup` no novo.
- Limpar os dados do navegador ou desinstalar a aplicacao pode apagar os registos locais se nao houver backup.

## Atualizacoes

Sempre que enviar alteracoes ao ramo `main`, o GitHub Actions publica automaticamente a nova versao.
