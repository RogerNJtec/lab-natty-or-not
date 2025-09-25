<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Natty or Not - O Poder das IAs Generativas</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap');
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Inter', sans-serif;
            line-height: 1.6;
            color: #2d3748;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
        }
        
        .container {
            max-width: 800px;
            margin: 0 auto;
            background: white;
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
            min-height: 100vh;
        }
        
        .page {
            padding: 60px 80px;
            page-break-after: always;
            min-height: calc(100vh - 120px);
        }
        
        .cover {
            background: linear-gradient(135deg, #4f46e5 0%, #7c3aed 50%, #ec4899 100%);
            color: white;
            text-align: center;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            position: relative;
            overflow: hidden;
        }
        
        .cover::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><defs><pattern id="grid" width="10" height="10" patternUnits="userSpaceOnUse"><path d="M 10 0 L 0 0 0 10" fill="none" stroke="rgba(255,255,255,0.1)" stroke-width="0.5"/></pattern></defs><rect width="100" height="100" fill="url(%23grid)"/></svg>') repeat;
            opacity: 0.3;
        }
        
        .cover h1 {
            font-size: 3.5rem;
            font-weight: 700;
            margin-bottom: 20px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
            position: relative;
            z-index: 1;
        }
        
        .cover h2 {
            font-size: 1.5rem;
            font-weight: 300;
            margin-bottom: 40px;
            opacity: 0.9;
            position: relative;
            z-index: 1;
        }
        
        .robot-icon {
            font-size: 8rem;
            margin: 40px 0;
            position: relative;
            z-index: 1;
        }
        
        .hashtag {
            font-size: 1.2rem;
            font-weight: 600;
            background: rgba(255,255,255,0.2);
            padding: 10px 20px;
            border-radius: 25px;
            position: relative;
            z-index: 1;
        }
        
        h1 {
            color: #4f46e5;
            font-size: 2.5rem;
            font-weight: 700;
            margin-bottom: 30px;
            border-bottom: 3px solid #4f46e5;
            padding-bottom: 15px;
        }
        
        h2 {
            color: #7c3aed;
            font-size: 1.8rem;
            font-weight: 600;
            margin: 30px 0 20px 0;
        }
        
        h3 {
            color: #ec4899;
            font-size: 1.4rem;
            font-weight: 600;
            margin: 25px 0 15px 0;
        }
        
        p {
            margin-bottom: 20px;
            font-size: 1.1rem;
            text-align: justify;
        }
        
        .highlight {
            background: linear-gradient(120deg, #fef3c7 0%, #fde68a 100%);
            padding: 20px;
            border-radius: 10px;
            border-left: 4px solid #f59e0b;
            margin: 25px 0;
            font-weight: 500;
        }
        
        .tool-box {
            background: linear-gradient(120deg, #dbeafe 0%, #bfdbfe 100%);
            padding: 20px;
            border-radius: 10px;
            border-left: 4px solid #3b82f6;
            margin: 25px 0;
        }
        
        .step-box {
            background: linear-gradient(120deg, #dcfce7 0%, #bbf7d0 100%);
            padding: 20px;
            border-radius: 10px;
            border-left: 4px solid #10b981;
            margin: 25px 0;
        }
        
        ul {
            margin: 20px 0;
            padding-left: 30px;
        }
        
        li {
            margin-bottom: 10px;
            font-size: 1.1rem;
        }
        
        .emoji {
            font-size: 1.5rem;
            margin: 0 5px;
        }
        
        .page-number {
            position: absolute;
            bottom: 30px;
            right: 50%;
            transform: translateX(50%);
            color: #6b7280;
            font-size: 0.9rem;
        }
        
        .intro-page {
            background: linear-gradient(120deg, #f3f4f6 0%, #e5e7eb 100%);
            border-radius: 15px;
            margin: -60px -80px;
            padding: 60px 80px;
        }
        
        @media print {
            body {
                background: white;
            }
            .page {
                page-break-after: always;
            }
            .container {
                box-shadow: none;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- CAPA -->
        <div class="page cover">
            <div class="robot-icon">🤖💪</div>
            <h1>Natty or Not</h1>
            <h2>Como as IAs Generativas Estão Redefinindo a Criatividade</h2>
            <p style="font-size: 1.2rem; margin: 20px 0;">Um Guia para Entender e Criar com Tecnologias do Futuro</p>
            <div class="hashtag">#LabDIONattyOrNot</div>
        </div>

        <!-- PÁGINA DE APRESENTAÇÃO -->
        <div class="page">
            <div class="intro-page">
                <h1>Bem-vindo ao Mundo das IAs Generativas! <span class="emoji">🚀</span></h1>
                
                <p>Você já ouviu falar em "Natty or Not" no fisiculturismo? É aquela pergunta clássica: "Esse shape é natural ou turbinado?" <span class="emoji">🤔</span></p>
                
                <p>No mundo da tecnologia, as IAs Generativas são como atletas de elite, criando textos, imagens, vídeos e até músicas que parecem 100% humanas. Elas são tão boas no que fazem que fica difícil distinguir se o conteúdo foi criado por uma pessoa ou por uma máquina.</p>
                
                <p>Neste e-book, vamos explorar como essas ferramentas funcionam, como usá-las e por que elas estão revolucionando a criatividade. Preparado para treinar sua mente e descobrir o poder das IAs? <span class="emoji">💪</span></p>
                
                <div class="highlight">
                    <strong>O que você vai aprender:</strong><br>
                    • Como funcionam as IAs Generativas<br>
                    • As melhores ferramentas disponíveis<br>
                    • Como criar projetos incríveis<br>
                    • Dicas práticas para começar hoje mesmo
                </div>
                
                <p style="text-align: center; font-size: 1.2rem; color: #4f46e5; font-weight: 600;">#LabDIONattyOrNot</p>
            </div>
            <div class="page-number">2</div>
        </div>

        <!-- CAPÍTULO 1 -->
        <div class="page">
            <h1>Capítulo 1: O que são IAs Generativas? <span class="emoji">🧠</span></h1>
            <h2>O "Treino" por Trás da Magia</h2>
            
            <p>IAs Generativas são modelos de inteligência artificial que criam conteúdos completamente novos a partir de dados que aprenderam durante seu "treinamento". Imagine como funciona: elas analisam milhões de exemplos de textos, imagens ou áudios e aprendem os padrões por trás de cada tipo de conteúdo.</p>
            
            <div class="highlight">
                <strong>Analogia com Fisiculturismo:</strong><br>
                "Assim como um atleta treina com pesos para construir músculos, as IAs treinam com dados para criar conteúdos incríveis. Quanto mais 'treino' (dados), melhor o 'shape' (resultado)!"
            </div>
            
            <h3>Exemplos Práticos na Prática:</h3>
            
            <ul>
                <li><strong>Textos:</strong> ChatGPT escrevendo histórias, artigos, poemas e até código de programação</li>
                <li><strong>Imagens:</strong> DALL-E e MidJourney criando artes fotorrealistas a partir de simples descrições</li>
                <li><strong>Vídeos:</strong> Synthesia gerando apresentadores virtuais que parecem pessoas reais</li>
                <li><strong>Áudios:</strong> ElevenLabs criando vozes sintéticas indistinguíveis de vozes humanas</li>
            </ul>
            
            <p>O mais impressionante é que essas IAs não apenas copiam o que viram antes - elas combinam elementos de formas criativas para gerar algo totalmente novo. É como se fossem artistas digitais com uma memória fotográfica de tudo que já foi criado na internet.</p>
            
            <div class="highlight">
                <strong>O Segredo do Sucesso:</strong><br>
                "O segredo é o 'treino' com grandes quantidades de dados, mas o resultado parece tão natural que você pergunta: 'É natty ou IA?'"
            </div>
            
            <div class="page-number">3</div>
        </div>

        <!-- CAPÍTULO 2 -->
        <div class="page">
            <h1>Capítulo 2: Ferramentas para Criar seu "Shape Digital" <span class="emoji">🛠️</span></h1>
            <h2>As Melhores IAs para o seu Arsenal</h2>
            
            <p>Agora que você entende o conceito, é hora de conhecer as ferramentas que vão turbinar sua criatividade. Cada uma tem sua especialidade, como diferentes equipamentos em uma academia.</p>
            
            <div class="tool-box">
                <h3>🤖 Para Textos e Conversas:</h3>
                <ul>
                    <li><strong>Grok (xAI):</strong> Criação de textos inteligentes e respostas criativas</li>
                    <li><strong>ChatGPT:</strong> O mais versátil para qualquer tipo de texto</li>
                    <li><strong>Claude:</strong> Excelente para análises detalhadas e textos longos</li>
                </ul>
            </div>
            
            <div class="tool-box">
                <h3>🎨 Para Imagens e Arte:</h3>
                <ul>
                    <li><strong>MidJourney:</strong> Artes impressionantes e fotorrealistas</li>
                    <li><strong>DALL-E:</strong> Integrado ao ChatGPT, ótimo para iniciantes</li>
                    <li><strong>Stable Diffusion:</strong> Gratuito e personalizável</li>
                </ul>
            </div>
            
            <div class="tool-box">
                <h3>🎬 Para Vídeos e Apresentações:</h3>
                <ul>
                    <li><strong>Synthesia:</strong> Avatares virtuais que falam qualquer texto</li>
                    <li><strong>D-ID:</strong> Transforma fotos em vídeos falantes</li>
                    <li><strong>Runway:</strong> Edição de vídeo com IA</li>
                </ul>
            </div>
            
            <div class="tool-box">
                <h3>🎵 Para Áudios e Vozes:</h3>
                <ul>
                    <li><strong>ElevenLabs:</strong> Vozes sintéticas ultra-realistas</li>
                    <li><strong>Mubert:</strong> Música gerada por IA</li>
                    <li><strong>Adobe Podcast:</strong> Melhora qualidade de áudio automaticamente</li>
                </ul>
            </div>
            
            <h3>Dicas para Iniciantes: <span class="emoji">💡</span></h3>
            
            <div class="step-box">
                <p><strong>1. Comece com versões gratuitas:</strong> Quase todas as ferramentas oferecem trials ou planos free</p>
                <p><strong>2. Teste prompts simples:</strong> "Crie uma imagem de um robô futurista em uma academia"</p>
                <p><strong>3. Seja específico:</strong> Quanto mais detalhado o prompt, melhor o resultado</p>
                <p><strong>4. Pratique regularmente:</strong> Como qualquer habilidade, melhora com a prática</p>
            </div>
            
            <div class="highlight">
                <strong>Lembre-se:</strong><br>
                "Essas ferramentas são como suplementos: elas turbinam sua criatividade, mas o talento e a visão são seus!"
            </div>
            
            <div class="page-number">4</div>
        </div>

        <!-- CAPÍTULO 3 -->
        <div class="page">
            <h1>Capítulo 3: Criando um Projeto "Natty" com IA <span class="emoji">🏗️</span></h1>
            <h2>Do Zero ao Shape Perfeito</h2>
            
            <p>Agora vamos colocar a mão na massa! Vou te mostrar um processo passo a passo para criar um projeto completo usando IAs Generativas. É como montar um treino completo na academia - cada exercício tem seu propósito.</p>
            
            <h3>Passo a Passo Completo: <span class="emoji">📋</span></h3>
            
            <div class="step-box">
                <h3>1. Definindo a Ideia 💡</h3>
                <p>Escolha um tema que te inspire. Para este e-book, escolhi explicar IAs usando analogias do fisiculturismo - algo divertido e educativo ao mesmo tempo.</p>
                <p><strong>Dica:</strong> Pense em algo que una seus interesses pessoais com tecnologia.</p>
            </div>
            
            <div class="step-box">
                <h3>2. Criando o Roteiro 📝</h3>
                <p>Use o Grok ou ChatGPT para estruturar suas ideias:</p>
                <p><em>"Crie um roteiro para um e-book sobre IAs Generativas usando analogias do fisiculturismo, com tom descontraído e educativo"</em></p>
            </div>
            
            <div class="step-box">
                <h3>3. Gerando os Visuais 🎨</h3>
                <p>Com MidJourney ou DALL-E, crie imagens que complementem seu conteúdo:</p>
                <p><em>"Um robô musculoso levantando pesos digitais em uma academia futurista, estilo vibrante e cinematográfico"</em></p>
            </div>
            
            <div class="step-box">
                <h3>4. Produzindo o Conteúdo Final 🚀</h3>
                <p>Monte tudo usando ferramentas como Canva para design ou até mesmo HTML/CSS para um resultado mais profissional.</p>
            </div>
            
            <div class="step-box">
                <h3>5. Organizando no GitHub 📁</h3>
                <p>Crie um repositório organizado para compartilhar seu trabalho:</p>
                <ul>
                    <li>README.md explicando o projeto</li>
                    <li>Pasta assets/ com imagens e arquivos</li>
                    <li>O e-book final em PDF</li>
                </ul>
            </div>
            
            <h3>Exemplo Real: Este E-book! <span class="emoji">📖</span></h3>
            
            <p>Este próprio e-book foi criado seguindo exatamente este processo:</p>
            
            <ul>
                <li><strong>Roteiro:</strong> Gerado com base no documento fornecido</li>
                <li><strong>Design:</strong> Criado com HTML/CSS responsivo</li>
                <li><strong>Conteúdo:</strong> Estruturado para ser educativo e envolvente</li>
                <li><strong>Resultado:</strong> Um e-book profissional em minutos!</li>
            </ul>
            
            <div class="highlight">
                <strong>Dica de Ouro:</strong><br>
                "Teste, ajuste e refine, como um treino na academia. O resultado final vai surpreender! Não tenha medo de iterar - cada versão fica melhor que a anterior."
            </div>
            
            <div class="page-number">5</div>
        </div>

        <!-- CAPÍTULO 4 -->
        <div class="page">
            <h1>Capítulo 4: Resultados e Impactos <span class="emoji">🎯</span></h1>
            <h2>Mostrando o Shape nas Redes</h2>
            
            <h3>Resultados do Projeto: <span class="emoji">🏆</span></h3>
            
            <p>Quando você terminar seu projeto, os resultados vão te impressionar. Veja o que conseguimos alcançar:</p>
            
            <ul>
                <li><strong>E-book profissional:</strong> Design moderno e conteúdo envolvente</li>
                <li><strong>Produção rápida:</strong> O que levaria dias foi feito em poucas horas</li>
                <li><strong>Qualidade alta:</strong> Resultado indistinguível de trabalhos "natty"</li>
                <li><strong>Repositório organizado:</strong> Pronto para compartilhamento no GitHub</li>
            </ul>
            
            <h3>O Impacto das IAs Generativas: <span class="emoji">🌍</span></h3>
            
            <div class="tool-box">
                <h4>Democratização da Criatividade</h4>
                <p>Antes, criar conteúdo profissional exigia anos de experiência em design, escrita ou produção. Hoje, qualquer pessoa com uma boa ideia pode criar algo impressionante.</p>
            </div>
            
            <div class="tool-box">
                <h4>Aplicações Infinitas</h4>
                <ul>
                    <li><strong>Marketing:</strong> Campanhas personalizadas em minutos</li>
                    <li><strong>Educação:</strong> Material didático adaptado para cada aluno</li>
                    <li><strong>Entretenimento:</strong> Histórias, jogos e experiências únicas</li>
                    <li><strong>Negócios:</strong> Automação de processos criativos</li>
                </ul>
            </div>
            
            <div class="tool-box">
                <h4>Revolução no Trabalho Criativo</h4>
                <p>As IAs não substituem a criatividade humana - elas a amplificam. Designers, escritores e criadores agora podem focar mais na estratégia e menos na execução repetitiva.</p>
            </div>
            
            <h3>Compartilhe seu Trabalho: <span class="emoji">📱</span></h3>
            
            <div class="step-box">
                <p><strong>1. Suba no GitHub:</strong> Organize seu repositório com README detalhado</p>
                <p><strong>2. Use a hashtag:</strong> Compartilhe com #LabDIONattyOrNot</p>
                <p><strong>3. Inspire outros:</strong> Explique seu processo e aprendizados</p>
                <p><strong>4. Continue criando:</strong> Cada projeto é uma oportunidade de aprender</p>
            </div>
            
            <div class="highlight">
                <strong>Convite Especial:</strong><br>
                "Suba seu projeto no GitHub e compartilhe com #LabDIONattyOrNot para inspirar outros! A comunidade está esperando para ver sua criação."
            </div>
            
            <p>Lembre-se: cada projeto que você cria com IA é uma demonstração do potencial dessa tecnologia. Você não está apenas aprendendo - está sendo parte de uma revolução criativa.</p>
            
            <div class="page-number">6</div>
        </div>

        <!-- CAPÍTULO 5 -->
        <div class="page">
            <h1>Capítulo 5: Reflexão - Natty ou Não? <span class="emoji">🤔</span></h1>
            <h2>O Desafio de Criar com IA</h2>
            
            <p>Chegou o momento da reflexão mais importante: depois de criar com IA, o resultado é realmente seu? Esta é uma pergunta que vai definir o futuro da criatividade.</p>
            
            <h3>Reflexão sobre o Processo: <span class="emoji">💭</span></h3>
            
            <div class="highlight">
                <strong>A Analogia Perfeita:</strong><br>
                "Criar com IA é como treinar com um personal trainer: você tem ajuda especializada, orientação profissional e ferramentas melhores, mas o esforço criativo, a visão e a dedicação são 100% seus."
            </div>
            
            <h3>Os Desafios Reais: <span class="emoji">⚡</span></h3>
            
            <div class="tool-box">
                <h4>Ajustar Prompts para Resultados Realistas</h4>
                <p>Como um atleta ajustando pesos e repetições, você precisa refinar suas instruções para conseguir exatamente o que imagina. Isso exige prática e paciência.</p>
            </div>
            
            <div class="tool-box">
                <h4>Escolher as Ferramentas Certas</h4>
                <p>Cada IA tem suas especialidades. Saber quando usar MidJourney vs DALL-E, ou Grok vs ChatGPT, faz toda a diferença no resultado final.</p>
            </div>
            
            <div class="tool-box">
                <h4>Manter a Criatividade Humana</h4>
                <p>O maior desafio é não se tornar dependente da IA. Ela deve amplificar suas ideias, não substituí-las.</p>
            </div>
            
            <h3>As Recompensas: <span class="emoji">🎁</span></h3>
            
            <ul>
                <li><strong>Eficiência Incrível:</strong> Projetos que levavam semanas agora levam horas</li>
                <li><strong>Criatividade Amplificada:</strong> Suas ideias ganham vida de formas impossíveis antes</li>
                <li><strong>Resultados Impressionantes:</strong> Qualidade profissional ao alcance de todos</li>
                <li><strong>Aprendizado Contínuo:</strong> Cada projeto ensina algo novo</li>
            </ul>
            
            <h3>A Pergunta Final: <span class="emoji">❓</span></h3>
            
            <div class="step-box">
                <p><strong>"No fim, o que importa é o resultado. Natty ou não, o que você criou é incrível?"</strong></p>
                
                <p>Pense assim: quando um atleta usa suplementos legais, equipamentos modernos e técnicas avançadas, seu físico deixa de ser impressionante? Não! O que importa é o resultado, o esforço e a dedicação por trás.</p>
                
                <p>Com IAs Generativas é a mesma coisa. Você está usando as melhores ferramentas disponíveis para materializar sua criatividade. O "shape digital" final é seu, e isso é o que realmente importa.</p>
            </div>
            
            <div class="highlight">
                <strong>Reflexão Final:</strong><br>
                "A questão não é se é 'natty' ou não. A questão é: você está criando algo que adiciona valor ao mundo? Se sim, parabéns - você está fazendo tudo certo!"
            </div>
            
            <div class="page-number">7</div>
        </div>

        <!-- CONCLUSÃO -->
        <div class="page">
            <h1>Seu Shape Digital Está Pronto! <span class="emoji">🎉</span></h1>
            
            <p>Chegamos ao final desta jornada, e que jornada foi essa! Você descobriu o poder das IAs Generativas, aprendeu a usar as melhores ferramentas e criou seu primeiro projeto. Agora você faz parte de uma nova geração de criadores digitais.</p>
            
            <h2>O que Você Conquistou: <span class="emoji">🏅</span></h2>
            
            <div class="tool-box">
                <ul>
                    <li><strong>Conhecimento:</strong> Entendeu como funcionam as IAs Generativas</li>
                    <li><strong>Ferramentas:</strong> Conhece as melhores IAs para cada tipo de conteúdo</li>
                    <li><strong>Processo:</strong> Domina o passo a passo para criar projetos completos</li>
                    <li><strong>Visão:</strong> Compreende o impacto dessas tecnologias no futuro</li>
                </ul>
            </div>
            
            <h2>Seus Próximos Passos: <span class="emoji">🚀</span></h2>
            
            <div class="step-box">
                <h3>1. Continue Treinando 💪</h3>
                <p>Como qualquer habilidade, criar com IA melhora com a prática. Teste novas ferramentas, experimente diferentes prompts, ouse ser criativo.</p>
            </div>
            
            <div class="step-box">
                <h3>2. Compartilhe seus Projetos 📢</h3>
                <p>Faça fork do repositório base, crie seu conteúdo e compartilhe com #LabDIONattyOrNot. A comunidade quer ver sua criação!</p>
            </div>
            
            <div class="step-box">
                <h3>3. Inspire Outros 🌟</h3>
                <p>Documente seu processo, ensine o que aprendeu, ajude outros a dar os primeiros passos. O conhecimento cresce quando é compartilhado.</p>
            </div>
            
            <div class="step-box">
                <h3>4. Mantenha-se Atualizado 📚</h3>
                <p>O mundo das IAs evolui rapidamente. Siga as novidades, teste novas ferramentas, adapte-se às mudanças.</p>
            </div>
            
            <h2>Uma Última Reflexão: <span class="emoji">💎</span></h2>
            
            <div class="highlight">
                <p><strong>As IAs Generativas são o futuro da criatividade, mas você é o presente.</strong></p>
                <p>Essas ferramentas são poderosas, mas sem sua visão, sua criatividade e sua paixão, elas são apenas código. O que faz a diferença é como você as usa para expressar suas ideias e impactar o mundo.</p>
            </div>
            
            <p>Agora vá lá e mostre ao mundo seu shape digital! O próximo grande projeto é seu, e mal podemos esperar para ver o que você vai criar.</p>
            
            <p style="text-align: center; font-size: 1.5rem; color: #4f46e5; font-weight: 700; margin-top: 40px;">
                Continue treinando, testando e criando.<br>
                O futuro é generativo, e você faz parte dele!<br>
                <span class="emoji">💪🤖✨</span>
            </p>
            
            <div class="page-number">8</div>
        </div>

        <!-- REFERÊNCIAS -->
        <div class="page">
            <h1>Referências e Links Úteis <span class="emoji">🔗</span></h1>
            
            <h2>Repositório Base:</h2>
            <div class="tool-box">
                <p><strong>GitHub DIO:</strong> https://github.com/digitalinnovationone/lab-natty-or-not</p>
                <p>Fork este repositório para começar seu próprio projeto!</p>
            </div>
            
            <h2>Ferramentas Mencionadas: <span class="emoji">🛠️</span></h2>
            
            <div class="tool-box">
                <h3>🤖 IAs de Texto:</h3>
                <ul>
                    <li><strong>Grok (xAI):</strong> x.ai - Acesso via plataforma X</li>
                    <li><strong>ChatGPT:</strong> chat.openai.com - OpenAI</li>
                    <li><strong>Claude:</strong> claude.ai - Anthropic</li>
                </ul>
            </div>
            
            <div class="tool-box">
                <h3>🎨 IAs de Imagem:</h3>
                <ul>
                    <li><strong>MidJourney:</strong> midjourney.com - Via Discord</li>
                    <li><strong>DALL-E:</strong> Integrado ao ChatGPT Plus</li>
                    <li><strong>Stable Diffusion:</strong> stability.ai - Versões gratuitas disponíveis</li>
                </ul>
            </div>
            
            <div class="tool-box">
                <h3>🎬 IAs de Vídeo:</h3>
                <ul>
                    <li><strong>Synthesia:</strong> synthesia.io - Avatares virtuais</li>
                    <li><strong>D-ID:</strong> d-id.com - Fotos que falam</li>
                    <li><strong>Runway:</strong> runwayml.com - Edição com IA</li>
                </ul>
            </div>
            
            <div class="tool-box">
                <h3>🎵 IAs de Áudio:</h3>
                <ul>
                    <li><strong>ElevenLabs:</strong> elevenlabs.io - Vozes sintéticas</li>
                    <li><strong>Mubert:</strong> mubert.com - Música por IA</li>
                    <li><strong>Adobe Podcast:</strong> podcast.adobe.com - Melhoria de áudio</li>
                </ul>
            </div>
            
            <div class="tool-box">
                <h3>🎨 Design e Produção:</h3>
                <ul>
                    <li><strong>Canva:</strong> canva.com - Design gráfico com IA</li>
                    <li><strong>Figma:</strong> figma.com - Design colaborativo</li>
                    <li><strong>Notion:</strong> notion.so - Organização de projetos</li>
                </ul>
            </div>
            
            <h2>Inspiração e Aprendizado: <span class="emoji">📚</span></h2>
            
            <ul>
                <li><strong>Base10's Trend Map Generative AI:</strong> Mapa de tendências em IA</li>
                <li><strong>AI News:</strong> Mantenha-se atualizado com as novidades</li>
                <li><strong>GitHub:</strong> Explore projetos da comunidade</li>
                <li><strong>YouTube:</strong> Tutoriais e cases de sucesso</li>
            </ul>
            
            <div class="page-number">9</div>
        </div>

        <!-- APÊNDICE -->
        <div class="page">
            <h1>Apêndice: Prompts e Dicas Práticas <span class="emoji">📋</span></h1>
            
            <h2>Prompts Sugeridos para Diferentes Situações:</h2>
            
            <div class="step-box">
                <h3>📝 Para Textos Criativos:</h3>
                <ul>
                    <li><em>"Escreva um parágrafo explicando [tema] usando analogias do [área de interesse]"</em></li>
                    <li><em>"Crie um roteiro para apresentação sobre [tópico] com tom [descontraído/formal/técnico]"</em></li>
                    <li><em>"Transforme estas informações técnicas em linguagem simples para iniciantes"</em></li>
                </ul>
            </div>
            
            <div class="step-box">
                <h3>🎨 Para Imagens Impressionantes:</h3>
                <ul>
                    <li><em>"Um robô futurista [ação] em uma [ambiente], estilo [cinematográfico/artístico/realista], cores vibrantes"</em></li>
                    <li><em>"Logotipo minimalista para [projeto], usando cores [paleta], estilo moderno"</em></li>
                    <li><em>"Infográfico sobre [tema], layout limpo, ícones simples, fundo [cor/gradiente]"</em></li>
                </ul>
            </div>
            
            <div class="step-box">
                <h3>🎬 Para Vídeos e Apresentações:</h3>
                <ul>
                    <li><em>"Avatar profissional apresentando [tópico] de forma didática e envolvente"</em></li>
                    <li><em>"Script para vídeo de 2 minutos explicando [conceito] para [público-alvo]"</em></li>
                    <li><em>"Apresentação visual sobre [tema] com transições suaves e design moderno"</em></li>
                </ul>
            </div>
            
            <h2>Dicas de Git e GitHub: <span class="emoji">💾</span></h2>
            
            <div class="tool-box">
                <h3>Comandos Básicos:</h3>
                <pre style="background: #1f2937; color: #e5e7eb; padding: 20px; border-radius: 10px; font-family: 'Courier New', monospace;">
# Clonar repositório
git clone [URL-do-repositório]

# Adicionar arquivos
git add .

# Fazer commit
git commit -m "Adiciona e-book sobre IAs Generativas"

# Enviar para GitHub
git push origin main

# Criar nova branch
git checkout -b meu-projeto

# Fazer fork via interface web do GitHub
                </pre>
            </div>
            
            <h2>Estrutura de Repositório Recomendada: <span class="emoji">📁</span></h2>
            
            <div class="tool-box">
                <pre style="background: #f3f4f6; padding: 20px; border-radius: 10px; font-family: 'Courier New', monospace;">
lab-natty-or-not/
├── README.md                 # Documentação principal
├── assets/                   # Arquivos de mídia
│   ├── capa.png             # Capa do projeto
│   ├── imagens/             # Imagens geradas
│   └── videos/              # Vídeos (se houver)
├── src/                     # Código fonte
│   ├── prompts.md           # Prompts utilizados
│   └── processo.md          # Documentação do processo
├── output/                  # Resultados finais
│   ├── ebook.pdf           # E-book final
│   └── apresentacao.pptx   # Apresentação (se houver)
└── docs/                   # Documentação adicional
    └── reflexao.md         # Reflexões sobre o projeto
                </pre>
            </div>
            
            <h2>Template de README.md: <span class="emoji">📄</span></h2>
            
            <div class="step-box">
                <pre style="background: #1f2937; color: #e5e7eb; padding: 20px; border-radius: 10px; font-family: 'Courier New', monospace; font-size: 0.9rem;">
# Meu Projeto IA Generativa

## 📒 Descrição
Breve descrição do seu projeto e objetivos.

## 🤖 Tecnologias Utilizadas
- [IA 1]: para [função]
- [IA 2]: para [função]
- [Ferramenta]: para [função]

## 🧐 Processo de Criação
Explique seu processo passo a passo...

## 🚀 Resultados
Apresente os resultados finais...

## 💭 Reflexão
Suas reflexões sobre o processo...

## 🔗 Links Úteis
- [Recurso 1]
- [Recurso 2]

---
⌨️ com ❤️ por [Seu Nome] 😊
                </pre>
            </div>
            
            <div class="page-number">10</div>
        </div>

        <!-- PÁGINA FINAL -->
        <div class="page" style="background: linear-gradient(135deg, #4f46e5 0%, #7c3aed 50%, #ec4899 100%); color: white; text-align: center; display: flex; flex-direction: column; justify-content: center;">
            <div style="position: relative; z-index: 1;">
                <div style="font-size: 4rem; margin-bottom: 30px;">🤖💪✨</div>
                
                <h1 style="color: white; border-bottom: none; font-size: 3rem; text-shadow: 2px 2px 4px rgba(0,0,0,0.3);">Parabéns!</h1>
                
                <h2 style="font-size: 1.5rem; margin: 30px 0; opacity: 0.9;">Você completou sua jornada no mundo das IAs Generativas</h2>
                
                <div style="background: rgba(255,255,255,0.1); padding: 30px; border-radius: 15px; margin: 40px 0; backdrop-filter: blur(10px);">
                    <p style="font-size: 1.2rem; margin-bottom: 20px;">Agora é sua vez de criar, inovar e inspirar!</p>
                    <p style="font-size: 1rem;">Compartilhe seu projeto com a hashtag:</p>
                    <div style="font-size: 1.5rem; font-weight: 700; background: rgba(255,255,255,0.2); padding: 15px; border-radius: 25px; margin: 20px 0;">#LabDIONattyOrNot</div>
                </div>
                
                <div style="font-size: 1.2rem; margin-top: 40px;">
                    <p>O futuro é generativo.</p>
                    <p>O futuro é seu.</p>
                    <p><strong>Vamos criar juntos! 🚀</strong></p>
                </div>
            </div>
            
            <!-- Efeito de grade no fundo -->
            <div style="position: absolute; top: 0; left: 0; right: 0; bottom: 0; background: url('data:image/svg+xml,<svg xmlns=\"http://www.w3.org/2000/svg\" viewBox=\"0 0 100 100\"><defs><pattern id=\"grid\" width=\"10\" height=\"10\" patternUnits=\"userSpaceOnUse\"><path d=\"M 10 0 L 0 0 0 10\" fill=\"none\" stroke=\"rgba(255,255,255,0.1)\" stroke-width=\"0.5\"/></pattern></defs><rect width=\"100\" height=\"100\" fill=\"url(%23grid)\"/></svg>') repeat; opacity: 0.3;"></div>
        </div>
    </div>

    <script>
        // Função para gerar PDF
        function generatePDF() {
            window.print();
        }
        
        // Adicionar botão de download (opcional)
        document.addEventListener('DOMContentLoaded', function() {
            const button = document.createElement('button');
            button.innerHTML = '📄 Gerar PDF';
            button.style.cssText = `
                position: fixed;
                top: 20px;
                right: 20px;
                background: #4f46e5;
                color: white;
                border: none;
                padding: 10px 20px;
                border-radius: 25px;
                cursor: pointer;
                font-weight: 600;
                box-shadow: 0 4px 15px rgba(79, 70, 229, 0.3);
                z-index: 1000;
                transition: all 0.3s ease;
            `;
            button.onmouseover = () => button.style.background = '#3730a3';
            button.onmouseout = () => button.style.background = '#4f46e5';
            button.onclick = generatePDF;
            document.body.appendChild(button);
        });
        
        // Efeitos de scroll suaves
        document.addEventListener('DOMContentLoaded', function() {
            const pages = document.querySelectorAll('.page');
            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.style.opacity = '1';
                        entry.target.style.transform = 'translateY(0)';
                    }
                });
            }, { threshold: 0.1 });
            
            pages.forEach(page => {
                page.style.opacity = '0';
                page.style.transform = 'translateY(20px)';
                page.style.transition = 'all 0.6s ease';
                observer.observe(page);
            });
        });
    </script>
</body>
</html>
