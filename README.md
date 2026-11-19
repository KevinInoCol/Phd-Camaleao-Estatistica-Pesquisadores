# Estatística para Pesquisadores · AIMS Camaleão

Slides em HTML da aula **Estatística para Pesquisadores** (público multidisciplinar, abordagem intuitiva), de Johsac Isbac Gomez Sanchez, no Grupo de Estudos Camaleão ([AIMS] Artificial Intelligence through Multimodal Signal Processing).

Baseado no roteiro `../roadmap_aula_estatistica_pesquisadores.md` e revisado segundo `../observacion.md` `../observaciones_v2.md` `../observaciones_v3.md` e `../observaciones_v4.md` (fundo branco, acento celeste, 67 lâminas, blocos 0–8).

Revisão v2: momentos como receita única das 4 famílias; média/mediana/moda por tipo de dado e outras médias; TCL com a equação; “além da Normal” (paramétrico × não-paramétrico, kernels do global ao local) depois do TCL; ponte sobre o “trabalho” de cada distribuição; 3 zonas de decisão nos testes; erros α/β, poder e tamanho de efeito de volta; tabelas no estilo de artigo (Mann-Whitney, ANOVA/Kruskal-Wallis, letras do post-hoc); ponte para desenhos fatoriais/multivariados/Friedman; resíduos movidos para a regressão; rmcorr depois da regressão; bloco 8 reorganizado (variáveis latentes → PCA × AF → PCA → AF com hipóteses); mapa final dos métodos.

Revisão v3: função geradora de momentos e rótulos “Tendência (k = 1)…”; sem a lâmina média × mediana (a anterior já faz a ponte); TCL com tempos de espera exponenciais (assimetria 2/√n); sem as lâminas de erros α/β, poder e tamanho de efeito (e sem referências a elas no resto); KS com H₀ dentro da animação e “n pequeno → Shapiro-Wilk × n grande → KS”; tabelas “Independentes / Dependentes-pareados”, sem “posto médio”; letras do post-hoc coerentes com 3 grupos + aba com 4 grupos (a, ab, b, c); equações e hipóteses na regressão não linear e na logística; mapa PC1 × PC2 na PCA.

Revisão v4: “modelo de dados × modelo algorítmico” (Breiman) no Bloco 0; equações em HTML dentro dos SVG (outras médias, kernel com janela h, estatísticos t/U/t pareado/W, Mahalanobis com vértices das elipses, Λ de Wilks, regressão e logística só com os β e as hipóteses); lâmina-mapa ligada à estatística inferencial (bondade de ajuste primeiro) reutilizada como separador antes de cada tema; grupo C do post-hoc em 69,4 ± 4,6; PCA com aba “novos eixos” e tabela de dados → mapa PC1 × PC2; análise fatorial simplificada (6 → 2 latentes, só a H₀ principal); sem “Erros clássicos” e “Traga um caso”; referências completas no encerramento.

## Como abrir

Abra `index.html` no navegador. O arquivo é autocontido: todos os gráficos são gerados em SVG, sem imagens nem bibliotecas externas.

- `→` / espaço: avançar (nas lâminas animadas, avança passo a passo) · `←`: voltar · `F`: tela cheia
- `↓` / `↑`: pula para a próxima/anterior lâmina sem passar pelos passos
- `index.html#N` abre direto na lâmina N · `index.html?step=K#N` abre a lâmina N já no passo K
