Farinhas Cósmicas V3.2 — Tri-Ring Atom (Faces Centradas) + 3D opcional

• Faces ASCII realmente CENTRALIZADAS (bloco absoluto com flex centering) e animadas por frames (3–8), trocadas via JS leve (sem CDN).
• Tri-Ring ASCII (externo/meio/interno) alternados (CW/CCW/CW).
• Overlay 3D opcional (CDN Three.js): pontos com glow + linhas de órbita (fallback total offline/safe).
• Safe Mode: ?safe=1 (desliga 3D e desacelera). Respeita prefers-reduced-motion.

Personalização:
- Edite a lista `frames` no fim do arquivo (JS) para mudar os quadros por arquétipo.
- Ajuste velocidade de troca alterando `base` (ms) no JS (ex.: 520 → 380).
- CSS vars no :root: --r1/--r2/--r3, --speed1/2/3, --n1/2/3, --color, --faceSize.

Dica: se quiser um trio de frames só (3), deixe a lista com 3 strings; o loop respeita o comprimento automaticamente.
