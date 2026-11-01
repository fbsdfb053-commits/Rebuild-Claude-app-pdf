# FBPDF

Leitor de PDF Android nativo (Kotlin), redesenhado: tema Noite/Papel com destaque âmbar.

## Novidades do redesign
- Biblioteca inicial com "Continuar lendo" (capa, página onde parou, progresso).
- Leitor imersivo: toque no centro esconde/mostra as barras; bordas viram página; duplo toque dá zoom; deslizar troca de página.
- Dock flutuante de ferramentas, paleta de cores do marca-texto, borracha por toque.
- Seleção de texto contínua (várias linhas) e destaques unidos por linha ao salvar.
- Busca com trechos, grade de miniaturas, favoritos, leitura noturna da página.
- Novo ícone e temas (Noite, Papel, Automático).

## Compilar
Android Studio (JDK 17, SDK 35) ou `gradle assembleDebug`.
Com o GitHub Actions (`.github/workflows/android.yml`) o APK sai em Artifacts.
