<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfólio BI - Mauro Granito</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; }
        body { background-color: #f8f9fa; color: #333; line-height: 1.6; }
        .container { max-width: 1600px; margin: 0 auto; padding: 40px; }
        
        header { 
            text-align: center; 
            padding: 3rem 1rem; 
            background: linear-gradient(135deg, #2c3e50, #1a1a2e); 
            color: white; 
            margin-bottom: 3rem; 
            border-radius: 0 0 12px 12px;
        }
        header h1 { font-size: 2.5rem; margin-bottom: 0.5rem; font-weight: 300; }
        header .subtitle { font-size: 1.1rem; max-width: 700px; margin: 1rem auto; color: #ccc; }
        .contact-bar { margin-top: 1.5rem; font-size: 1rem; }
        .contact-bar a { color: #64b5f6; margin: 0 10px; text-decoration: none; font-weight: 500; }
        .contact-bar a:hover { text-decoration: underline; }
        
        .disclaimer { 
            background: #fff8e1; 
            border-left: 4px solid #ffb300; 
            padding: 1.2rem; 
            margin: 2rem 0; 
            border-radius: 0 4px 4px 0; 
            font-style: italic; 
            color: #5d4037;
            font-size: 0.95rem;
        }
        
        .dashboard-grid { 
            display: grid; 
            grid-template-columns: repeat(auto-fit, minmax(600px, 1fr)); 
            gap: 2.5rem; 
            margin-bottom: 3rem; 
        }
        @media (max-width: 768px) {
            .dashboard-grid { 
                grid-template-columns: 1fr; 
                gap: 2rem;
            }
            .container {
                padding: 20px;
            }
            header {
                padding: 2rem 1rem;
            }
            header h1 {
                font-size: 2rem;
            }
        }
        
        .dashboard-card { 
            background: white; 
            border-radius: 8px; 
            overflow: hidden; 
            box-shadow: 0 4px 12px rgba(0,0,0,0.05); 
            border: 1px solid #eaeaea;
            transition: all 0.25s ease;
        }
        .dashboard-card:hover { 
            transform: translateY(-4px); 
            box-shadow: 0 8px 20px rgba(0,0,0,0.08); 
        }
        
        .card-image { 
            width: 100%; 
            background: #f5f7fa; 
            text-align: center; 
            padding: 1.5rem; 
            border-bottom: 1px solid #eee; 
        }
        .card-image img { 
            max-width: 100%; 
            height: auto; 
            border-radius: 4px; 
            box-shadow: 0 2px 8px rgba(0,0,0,0.05);
        }
        
        .card-content { padding: 1.8rem; }
        .card-content h2 { 
            color: #2c3e50; 
            margin-bottom: 1rem; 
            font-size: 1.5rem; 
            font-weight: 600;
        }
        .card-content .context { 
            color: #555; 
            margin-bottom: 1rem; 
            line-height: 1.5;
        }
        .card-content .tech { 
            color: #666; 
            font-size: 0.9rem; 
            margin-bottom: 1.2rem;
            padding-bottom: 1rem;
            border-bottom: 1px solid #eee;
        }
        .card-content strong { color: #2c3e50; }
        .card-content ul { 
            padding-left: 1.2rem; 
            color: #555;
        }
        .card-content li { 
            margin-bottom: 0.5rem; 
            line-height: 1.4;
        }
        
        footer { 
            text-align: center; 
            padding: 2rem; 
            margin-top: 3rem; 
            color: #777; 
            font-size: 0.9rem;
            border-top: 1px solid #eee; 
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Portfólio de Dashboards</h1>
            <p class="subtitle">Mauro Granito - Analista de Dados & BI</p>
            <p class="subtitle">Soluções em Business Intelligence para transformar dados complexos em insights acionáveis.</p>
            <div class="contact-bar">
                <a href="mailto:mldgranito@gmail.com">mldgranito@gmail.com</a> |
                <a href="https://www.linkedin.com/in/mauro-lucas-granito" target="_blank">LinkedIn</a>
            </div>
        </div>
    </header>

    <div class="container">
        <div class="disclaimer">
            <strong>Observação:</strong> Todos os modelos abaixo foram criados com dados fictícios, com o objetivo de demonstrar a modelagem e a construção de visuais aplicados em contextos reais.
        </div>

        <div class="dashboard-grid">

            <div class="dashboard-card">
                <div class="card-image">
                    <img src="PBI%20-%20Motor%20de%20Crédito.png" alt="Dashboard Motor de Crédito">
                </div>
                <div class="card-content">
                    <h2>Motor de Crédito & Aprovação</h2>
                    <p class="context"><strong>Contexto:</strong> Dashboard central para o processo de análise e decisão de crédito, monitorando o fluxo de propostas desde a entrada até a aprovação final.</p>
                    <p class="tech"><strong>Tecnologias:</strong> Power BI, SQL, Integração de dados transacionais.</p>
                    <strong>Principais Funcionalidades:</strong>
                    <ul>
                        <li>Monitoramento em tempo real do volume de propostas, aprovações e reprovações.</li>
                        <li>Análise da taxa de aprovação por faixa de risco e score.</li>
                        <li>Diagnóstico dos principais motivos de reprovação para ação corretiva.</li>
                    </ul>
                </div>
            </div>

            <div class="dashboard-card">
                <div class="card-image">
                    <img src="PBI%20-%20Inadimplência.png" alt="Dashboard Inadimplência">
                </div>
                <div class="card-content">
                    <h2>Gestão de Risco e Inadimplência</h2>
                    <p class="context"><strong>Contexto:</strong> Sistema de monitoramento proativo da carteira de clientes, focado na identificação de sinais de inadimplência por safra e faixa de risco.</p>
                    <p class="tech"><strong>Tecnologias:</strong> Power BI, Modelo de dados estrela, DAX avançado.</p>
                    <strong>Principais Funcionalidades:</strong>
                    <ul>
                        <li>Acompanhamento da performance de pagamento por safra de contrato.</li>
                        <li>Segmentação da inadimplência por dias em atraso (>30, >60, >90).</li>
                        <li>Análise do valor exposto (FPD) por perfil de risco.</li>
                    </ul>
                </div>
            </div>

            <div class="dashboard-card">
                <div class="card-image"> 
                    <img src="PBI%20-%20VIsual%20de%20Acompanhamento%20de%20Planilha.png" alt="Dashboard Propostas Comerciais">
                </div>
                <div class="card-content">
                    <h2>Controle de Propostas Comerciais</h2>
                    <p class="context"><strong>Contexto:</strong> Painel de gestão operacional para o acompanhamento do pipeline de vendas B2B, desde a proposta até a efetivação do contrato.</p>
                    <p class="tech"><strong>Tecnologias:</strong> Power BI, Google Sheets, API.</p>
                    <strong>Principais Funcionalidades:</strong>
                    <ul>
                        <li>Visão do status das propostas (Aprovado, Reprovado, Em Andamento).</li>
                        <li>Análise dos motivos de reprovação para melhoria de processos.</li>
                        <li>Filtros dinâmicos por equipe comercial, data e tipo de solicitação.</li>
                    </ul>
                </div>
            </div>

            <div class="dashboard-card">
                <div class="card-image">
                    <img src="PBI%20-%20Tabela%20Simples.png" alt="Dashboard Tabela Farol">
                </div>
                <div class="card-content">
                    <h2>Farol de Gestão (Tableau de Controle)</h2>
                    <p class="context"><strong>Contexto:</strong> Tableau de bordo operacional ("farol") para monitorar a saúde e o status de diversos canais ou unidades de negócio.</p>
                    <p class="tech"><strong>Tecnologias:</strong> Power BI, Consultas diretas a banco de dados.</p>
                    <strong>Principais Funcionalidades:</strong>
                    <ul>
                        <li>Visualização geral dos canais de venda por farol (medida interna).</li>
                        <li>Visual de Tabela simples para download e análise detalhada.</li>
                    </ul>
                </div>
            </div>

        </div>
    </div>

    <footer>
        <div class="container">
            <p>Portfólio de Mauro Granito. Visualizações construídas com Power BI para demonstração de habilidades em análise de dados e Business Intelligence.</p>
        </div>
    </footer>
</body>
</html>
