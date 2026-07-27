<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Central GS - AI Level Maker</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #0b0f19;
            color: #f8fafc;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
        }

        header {
            background: rgba(15, 23, 42, 0.9);
            backdrop-filter: blur(10px);
            border-bottom: 1px solid #1e293b;
            padding: 1rem 2rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
            z-index: 100;
        }

        .logo {
            font-size: 1.5rem;
            font-weight: 800;
            background: linear-gradient(135deg, #00f2fe, #4facfe);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .badge {
            background: #0284c7;
            color: #fff;
            font-size: 0.7rem;
            padding: 3px 8px;
            border-radius: 12px;
            font-weight: bold;
        }

        main {
            max-width: 1000px;
            margin: 0 auto;
            padding: 2rem 1rem;
            flex: 1;
            width: 100%;
        }

        .hero {
            text-align: center;
            margin-bottom: 2.5rem;
        }

        .hero h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
            font-weight: 800;
        }

        .hero p {
            color: #94a3b8;
            font-size: 1.1rem;
        }

        .card {
            background: #111827;
            border: 1px solid #1f2937;
            border-radius: 16px;
            padding: 2rem;
            box-shadow: 0 10px 30px rgba(0,0,0,0.5);
        }

        .card-header {
            display: flex;
            align-items: center;
            gap: 12px;
            margin-bottom: 1.5rem;
        }

        .card-icon {
            width: 50px;
            height: 50px;
            background: linear-gradient(135deg, #00f2fe, #4facfe);
            border-radius: 12px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.8rem;
        }

        .card-title {
            font-size: 1.4rem;
            font-weight: 700;
        }

        .form-group {
            margin-bottom: 1.2rem;
        }

        .form-group label {
            display: block;
            font-size: 0.9rem;
            color: #cbd5e1;
            margin-bottom: 0.5rem;
            font-weight: 600;
        }

        .form-group input, .form-group textarea {
            width: 100%;
            padding: 12px 14px;
            background: #070a12;
            border: 1px solid #1f2937;
            border-radius: 8px;
            color: #fff;
            font-size: 0.95rem;
            outline: none;
            transition: border-color 0.2s;
        }

        .form-group textarea {
            height: 110px;
            resize: vertical;
        }

        .form-group input:focus, .form-group textarea:focus {
            border-color: #38bdf8;
        }

        .api-toggle {
            font-size: 0.85rem;
            color: #94a3b8;
            margin-bottom: 1rem;
            cursor: pointer;
            display: inline-block;
            text-decoration: underline;
        }

        .btn {
            width: 100%;
            padding: 14px;
            background: linear-gradient(135deg, #0284c7, #2563eb);
            color: white;
            border: none;
            border-radius: 8px;
            font-weight: 700;
            font-size: 1rem;
            cursor: pointer;
            transition: all 0.2s;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
        }

        .btn:hover {
            opacity: 0.9;
            transform: translateY(-2px);
        }

        .status-box {
            margin-top: 15px;
            padding: 12px;
            border-radius: 8px;
            font-size: 0.9rem;
            display: none;
            text-align: center;
        }

        .status-box.success {
            background: rgba(34, 197, 94, 0.15);
            color: #4ade80;
            border: 1px solid #22c55e;
        }

        .status-box.loading {
            background: rgba(56, 189, 248, 0.15);
            color: #38bdf8;
            border: 1px solid #0284c7;
        }

        footer {
            text-align: center;
            padding: 2rem;
            color: #475569;
            font-size: 0.85rem;
            border-top: 1px solid #111827;
            margin-top: auto;
        }
    </style>
</head>
<body>

    <header>
        <div class="logo">
            🤖 Central GS <span class="badge">IA Engine</span>
        </div>
    </header>

    <main>
        <section class="hero">
            <h1>Central GS AI</h1>
            <p>Digite em linguagem natural o nível que você quer e a IA criará o arquivo .gmd para você!</p>
        </section>

        <div class="card">
            <div class="card-header">
                <div class="card-icon">⚡</div>
                <div>
                    <div class="card-title">AI Geometry Dash Level Maker</div>
                    <small style="color: #64748b;">Powered by Central GS NLP & LLM</small>
                </div>
            </div>

            <div class="form-group">
                <label for="prompt">Descreva o seu nível para a IA (Prompt livre):</label>
                <textarea id="prompt" placeholder="Exemplo: Crie um nível difícil com cubo no início, depois portal de nave com teto de blocos, espinhos triplos, muitas orbs e transição para wave..."></textarea>
            </div>

            <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 1rem;">
                <div class="form-group">
                    <label for="levelName">Nome do Nível</label>
                    <input type="text" id="levelName" value="AI World 1">
                </div>
                <div class="form-group">
                    <label for="authorName">Autor</label>
                    <input type="text" id="authorName" value="CentralGS_AI">
                </div>
            </div>

            <!-- OPÇÃO AVANÇADA COM GEMINI KEY -->
            <span class="api-toggle" onclick="toggleApiKey()">🔑 Usar Chave de API da Google Gemini (Opcional)</span>
            <div class="form-group" id="apiKeyGroup" style="display: none;">
                <label for="geminiKey">Chave API do Gemini (deixe vazio para usar IA interna):</label>
                <input type="password" id="geminiKey" placeholder="Cole sua chave AIZASy...">
            </div>

            <button class="btn" onclick="processWithAI()">
                🤖 Processar com IA e Baixar (.gmd)
            </button>

            <div id="statusBox" class="status-box"></div>
        </div>
    </main>

    <footer>
        Central GS &copy; 2026 - Gerador de Níveis IA para Geometry Dash
    </footer>

    <script>
        function toggleApiKey() {
            const el = document.getElementById('apiKeyGroup');
            el.style.display = el.style.display === 'none' ? 'block' : 'none';
        }

        // IDs dos Objetos no Geometry Dash
        const OBJ = {
            BLOCK: 1,
            SPIKE: 8,
            SPIKE_SMALL: 9,
            ORB_YELLOW: 36,
            ORB_PINK: 141,
            PAD_YELLOW: 35,
            PORTAL_SHIP: 12,
            PORTAL_CUBE: 13,
            PORTAL_BALL: 47,
            PORTAL_UFO: 111,
            PORTAL_WAVE: 660,
            PORTAL_ROBOT: 744,
            PORTAL_SPIDER: 1331
        };

        async function processWithAI() {
            const prompt = document.getElementById('prompt').value;
            const levelName = document.getElementById('levelName').value || "AI Level";
            const author = document.getElementById('authorName').value || "Central GS";
            const geminiKey = document.getElementById('geminiKey').value.trim();
            const statusBox = document.getElementById('statusBox');

            if (!prompt) {
                alert("Por favor, digite uma instrução para a IA!");
                return;
            }

            statusBox.className = "status-box loading";
            statusBox.style.display = "block";
            statusBox.innerText = "🤖 A IA está interpretando seu prompt e gerando os blocos...";

            setTimeout(async () => {
                let generatedObjects = [];

                if (geminiKey) {
                    // MODO 1: IA Gemini Real (via API)
                    try {
                        generatedObjects = await callGeminiAPI(geminiKey, prompt);
                    } catch (e) {
                        console.error(e);
                        alert("Erro ao usar API do Gemini. Usando o motor de IA interno!");
                        generatedObjects = parsePromptInternally(prompt);
                    }
                } else {
                    // MODO 2: Processador de Linguagem Natural Interno (Nativo)
                    generatedObjects = parsePromptInternally(prompt);
                }

                // Criar arquivo .gmd
                exportGMD(levelName, author, prompt, generatedObjects);

                statusBox.className = "status-box success";
                statusBox.innerText = "✅ Nível gerado pela IA com sucesso e arquivo .gmd baixado!";
            }, 600);
        }

        // Processador de Linguagem Natural com IA Interno
        function parsePromptInternally(prompt) {
            const text = prompt.toLowerCase();
            let objects = [];

            function addObj(id, col, row) {
                let x = col * 30 + 15;
                let y = row * 30 + 15;
                objects.push(`1,${id},2,${x},3,${y}`);
            }

            // Análise da IA sobre intenção
            const isHard = text.includes('hard') || text.includes('difícil') || text.includes('dificil') || text.includes('demon') || text.includes('insano');
            const isLong = text.includes('longo') || text.includes('grande') || text.includes('extenso');
            
            const totalBlocks = isLong ? 120 : (isHard ? 80 : 50);

            // Modos de Jogo detectados na frase
            let modes = [];
            if (text.includes('nave') || text.includes('ship')) modes.push(OBJ.PORTAL_SHIP);
            if (text.includes('wave')) modes.push(OBJ.PORTAL_WAVE);
            if (text.includes('ufo')) modes.push(OBJ.PORTAL_UFO);
            if (text.includes('robô') || text.includes('robo') || text.includes('robot')) modes.push(OBJ.PORTAL_ROBOT);
            if (text.includes('aranha') || text.includes('spider')) modes.push(OBJ.PORTAL_SPIDER);
            if (text.includes('bola') || text.includes('ball')) modes.push(OBJ.PORTAL_BALL);

            // Se nenhum portal foi citado, faz uma mistura
            if (modes.length === 0) modes = [OBJ.PORTAL_CUBE];

            let currentMode = OBJ.PORTAL_CUBE;
            let currentCol = 0;

            // 1. Chão inicial
            for (let c = 0; c < totalBlocks; c++) {
                addObj(OBJ.BLOCK, c, 0);
            }

            // 2. Construção baseada no prompt
            for (let c = 5; c < totalBlocks - 5; c++) {
                
                // Transição de Portal solicitada
                if (c % 25 === 0 && modes.length > 0) {
                    currentMode = modes.shift(); // Pega o próximo portal pedido no texto
                    addObj(currentMode, c, 2);
                    continue;
                }

                // Gerar obstáculos baseados no modo atual
                if (currentMode === OBJ.PORTAL_CUBE || currentMode === OBJ.PORTAL_ROBOT) {
                    if (Math.random() < (isHard ? 0.35 : 0.2)) {
                        addObj(OBJ.SPIKE, c, 1);
                        if (isHard && Math.random() < 0.5) {
                            addObj(OBJ.SPIKE, c + 1, 1);
                            c++;
                        }
                        if (text.includes('orb') || Math.random() < 0.3) {
                            addObj(OBJ.ORB_YELLOW, c - 1, 3);
                        }
                    }
                } else if (currentMode === OBJ.PORTAL_SHIP || currentMode === OBJ.PORTAL_WAVE) {
                    // Adicionar teto para nave/wave
                    addObj(OBJ.BLOCK, c, 7);
                    if (Math.random() < 0.3) {
                        let y = Math.floor(Math.random() * 3) + 3;
                        addObj(OBJ.BLOCK, c, y);
                    }
                } else {
                    if (Math.random() < 0.25) {
                        addObj(OBJ.SPIKE, c, 1);
                    }
                }
            }

            return objects;
        }

        // Chamada à API do Gemini caso o usuário forneça a chave
        async function callGeminiAPI(key, promptText) {
            const response = await fetch(`https://generativelanguage.googleapis.com/v1beta/models/gemini-1.5-flash:generateContent?key=${key}`, {
                method: 'POST',
                headers: { 'Content-Type': 'application/json' },
                body: JSON.stringify({
                    contents: [{
                        parts: [{
                            text: `Você é um gerador de níveis do Geometry Dash. O usuário pediu: "${promptText}".
                            Retorne APENAS um JSON com o array de objetos no formato: [{"id": 1, "col": 0, "row": 0}, {"id": 8, "col": 5, "row": 1}]. Exemplo com blocos (id 1) e espinhos (id 8).`
                        }]
                    }]
                })
            });
            const data = await response.json();
            const textResponse = data.candidates[0].content.parts[0].text;
            const jsonMatch = textResponse.match(/\[.*\]/s);
            const rawObjs = JSON.parse(jsonMatch[0]);

            let objects = [];
            rawObjs.forEach(o => {
                let x = o.col * 30 + 15;
                let y = o.row * 30 + 15;
                objects.push(`1,${o.id},2,${x},3,${y}`);
            });
            return objects;
        }

        // Função de exportar para .gmd
        function exportGMD(name, author, promptText, objects) {
            const header = "kS38,1_40_2_125_3_255_4_40_5_125_6_255_7_255_8_255,kS39,1";
            const levelString = header + ";" + objects.join(";") + (objects.length > 0 ? ";" : "");
            const descB64 = btoa(unescape(encodeURIComponent("AI Prompt: " + promptText)));

            const gmdContent = `<?xml version="1.0"?>
<plist version="1.0" gcds="5">
	<dict>
		<k>k0</k><i>0</i>
		<k>k2</k><s>${name}</s>
		<k>k3</k><s>${descB64}</s>
		<k>k4</k><s>${levelString}</s>
		<k>k5</k><s>${author}</s>
		<k>k13</k><t/>
		<k>k21</k><i>1</i>
		<k>k45</k><i>0</i>
		<k>k80</k><i>63</i>
		<k>k88</k><i>0</i>
	</dict>
</plist>`;

            const fileName = `${name.replace(/\s+/g, '_')}_AI.gmd`;
            const blob = new Blob([gmdContent], { type: "text/xml;charset=utf-8" });
            const link = document.createElement("a");
            link.href = URL.createObjectURL(blob);
            link.download = fileName;
            link.click();
        }
    </script>
</body>
</html>
