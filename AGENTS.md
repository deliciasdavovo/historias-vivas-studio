# Histórias Vivas — regras de produção e publicação

Sincronização editorial com Direção de Personagens — Mitos, versão 2.9.30 (27/11/2026). Estas instruções orientam agentes e pessoas que criam ou revisam histórias nesta biblioteca. A central web exibe os prompts cadastrados; não gera os roteiros por si.

## Regra principal: contar uma história
- Antes de dividir em clipes, estudar uma versão identificada da obra e escrever o roteiro falado contínuo, com começo, desenvolvimento e desfecho. Distinguir adaptação de citação. Não inventar fatos, crimes, motivos ou conclusões como se fossem da fonte.
- O espectador leigo deve compreender a trama ouvindo apenas as falas: quem fez o quê, por quê quando conhecido, contra quem, como, e com qual consequência. Explicar condições de acordos, poderes, objetos mágicos, mudanças de estado e elipses antes de depender deles. Mistério deliberado não é lacuna causal.
- Cada cena avança um acontecimento concreto, com ação, reação e consequência ou preparação para a seguinte. Mostrar o que for filmável; nomear no áudio os fatos essenciais, mesmo quando a imagem também os mostra. Não substituir explicação por metáfora, piada ou instrução invisível ao espectador.
- Em mitos de punição, incluir o pior ato relevante atestado na versão escolhida e sua consequência; usar representação não gráfica e reação dos afetados quando pertinente. Não forçar vilania em outros contos.
- Abertura concreta, intrigante e compreensível nos primeiros três segundos, sem spoiler. Oralidade literária natural, variação de cadência, emoção que evolui, humor seco adulto nas contradições e personalidade. Encerramento fiel à obra, sem moral inventada, pergunta de engajamento ou loop obrigatório. Coda factual ou filosófica apenas quando pertinente, verificável e atribuída.

## Voz e continuidade sonora
- Gerar narração e diálogos **audíveis no próprio Pavo, em português do Brasil**. A regra de gerar vídeo mudo foi rejeitada: não impor dublagem posterior nem substituir voz por legenda.
- Narrador invisível HV-N01: voz masculina madura/grave, calorosa, experiente, ironia discreta. Preservar assinatura vocal canônica do plugin e diferenciar cada personagem. Narrador conecta eventos e esclarece causas; diálogos naturais podem conduzir clipes sem narrador quando a informação está clara. Nenhum clipe narrativo sem voz por padrão; silêncio dramático justificado é exceção. 
- Personagens têm desejos, reações e falas com intenção; interação com narrador e humor de personalidade quando orgânicos, sem cotas mecânicas. O narrador não aparece. Só o falante visível move a boca, sem sobreposição; durante voz off, os personagens reagem sem falar.
- Minutar falas literais por clipe, com falante, intenção e voz. Estimar por leitura oral com pausas, dividir em clipes em vez de atropelar ou eliminar fatos essenciais. Manter áudio, trilha discreta e efeitos coerentes entre clipes.

## Modelo Pavo/Pivo — todos os três estilos
- Clipes de **4 a 12 segundos**, vertical 9:16, conforme duração disponível no gerador (Agnes Video 2.5 Flash). Filme geralmente até dois minutos; não comprimir acontecimentos essenciais por uma meta arbitrária. A regra de 4–12 s substitui o limite anterior de 10 s.
- Um acontecimento principal por clipe, normalmente 2–3 intervalos orgânicos de ação/atuação/fotografia, cobrindo a duração. Mudanças significativas de informação visual, sem obrigar cortes a cada dois segundos. Fotografia aberta por padrão, personagens integrados ao ambiente, escala e posição claras, aproximações apenas motivadas.
- Elenco: IDs/nomes, referência coletiva A/B (uma ou duas folhas para a história), variantes e estado específico quando necessário. Preservar rigorosamente o guia aprovado; **não repetir descrições físicas completas** em todos os prompts. Identidade detalhada fica no estudo e no guia. Não clonar, misturar estilos ou incluir personagens não autorizados. Olhos com pálpebras, cores ricas controladas, consistência de materiais.
- Manter âncora visual literal do estilo escolhido no plugin: Paper Style Cinema, Guache 2D ou 3D artesanal. Claude por código mantém fluxo e estética próprios.

Estrutura de cada prompt autossuficiente, diretamente copiável:

1. `OBRIGATORIAMENTE, FALAS E NARRAÇÃO EM PORTUGUÊS DO BRASIL.`
2. Crie um vídeo de [4–12] segundos, vertical 9:16.
3. ESTILO: âncora literal do modo escolhido e áudio falado no próprio vídeo.
4. PERSONAGENS: IDs, nomes, referência pertinente, variantes e elenco autorizado.
5. CENÁRIO: lugar, luz, objetos, posições e estado inicial.
6. AÇÃO E FOTOGRAFIA: intervalos concretos, quem faz o quê, reação, resultado, câmera motivada. O acontecimento deve ficar inequívoco sem criar cabeçalhos técnicos redundantes.
7. FALAS E NARRAÇÃO (ou DIÁLOGOS): texto literal uma única vez, intervalos locais, nome/ID, voz e intenção. Se não houver narrador, declarar sua ausência. Manter assinatura HV-N01 quando ele fala.
8. SOM: efeitos, ambiência e trilha abaixo das vozes.
9. QUADRO FINAL: estado de saída, gesto, objeto e continuidade para o próximo clipe.
10. Restrições breves: somente falante visível move a boca, sem personagens extras, clones, textos ou legendas geradas.

## Auditoria obrigatória antes de entregar ou publicar
1. Ler roteiro falado sozinho e verificar todos os elos causais contra a fonte.
2. Extrair as falas dos **prompts finais** na ordem dos clipes e repetir o teste; conferir texto aprovado, referentes claros e tempo de fala.
3. Em cada transição, considerar somente o que o espectador já ouviu/viu: quem agiu, o que mudou, por que importa? Corrigir lacunas antes de publicar.
4. Conferir ação filmável, identidade/referências, voz, estados de entrada/saída e sincronia planejada. Não alegar teste de geração sem vídeo real.
5. Preservar histórias existentes, arquivos de vídeo locais e progresso. Não alterar texto aprovado sem autorização. Só cadastrar novas histórias autorizadas seguindo o formato de `stories/README.md`. Não publicar segredos ou dados privados.

Em caso de conflito com exemplos antigos, aplicar estas regras atuais e consultar o plugin para âncoras visuais e assinaturas vocais completas. A biblioteca armazena os resultados, não substitui o plugin nem garante comportamento do gerador.
