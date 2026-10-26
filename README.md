# Divisor 3D — Materializza

Site para separar modelos 3D em peças antes de imprimir e montar o orçamento da impressão.

- Abre **3MF** (inclusive pintado no Bambu Studio), **GLB** colorido (ex.: Tripo), **STL** e **OBJ**.
- Separa pelas **cores** ou pelas **emendas** da peça (olhos, bochechas, orelhas), com tampa reta ou peça embutida.
- Corte reto com encaixe (pino ou cavilha), se precisar.
- Baixa um .zip com um 3MF de todas as peças e um STL de cada.
- **Orçamento:** lê o tempo e os gramas do arquivo fatiado (.gcode.3mf) do Bambu Studio.
- Conta (Supabase): login por e-mail e senha ou Google; orçamentos e valores salvos.

Tudo roda no navegador: os arquivos 3D não são enviados para servidor nenhum.

Feito com Three.js, three-bvh-csg, JSZip e Supabase. Hospedado no Cloudflare Pages.
