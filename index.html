<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>Sistema Hidropônico Automatizado</title>
  <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Roboto', sans-serif;
    }
    body {
      background-color: #f8fafc;
      color: #2d3748;
    }
    header {
      background: linear-gradient(135deg, #1e3a8a 0%, #3b82f6 100%);
      color: white;
      padding: 20px;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 25px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }
    header img {
      height: 70px;
      filter: brightness(0) invert(1);
    }
    header h1 {
      font-size: 2rem;
      font-weight: 500;
      text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.2);
    }
    nav {
      background-color: #e2e8f0;
      display: flex;
      justify-content: center;
      gap: 15px;
      padding: 15px;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.05);
    }
    nav button {
      background: linear-gradient(to bottom, #3b82f6, #1d4ed8);
      color: white;
      border: none;
      padding: 12px 25px;
      cursor: pointer;
      border-radius: 8px;
      transition: all 0.3s ease;
      font-weight: 500;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    }
    nav button:hover {
      background: linear-gradient(to bottom, #2563eb, #1e40af);
      transform: translateY(-2px);
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.15);
    }
    .tab {
      display: none;
      padding: 25px;
      max-width: 1200px;
      margin: 0 auto;
    }
    .active {
      display: block;
      animation: fadeIn 0.5s ease;
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(10px); }
      to { opacity: 1; transform: translateY(0); }
    }
    .dashboard {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 25px;
      margin-top: 20px;
    }
    .card {
      background-color: white;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.05);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
      border-left: 4px solid #3b82f6;
    }
    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 10px 15px rgba(0, 0, 0, 0.1);
    }
    .label {
      font-weight: 500;
      color: #1e40af;
      font-size: 1rem;
      margin-bottom: 5px;
    }
    .value {
      font-size: 2rem;
      font-weight: 600;
      color: #1e3a8a;
    }
    textarea {
      width: 100%;
      height: 200px;
      padding: 15px;
      font-size: 1rem;
      border: 1px solid #cbd5e0;
      border-radius: 8px;
      resize: vertical;
      transition: border-color 0.3s ease;
    }
    textarea:focus {
      outline: none;
      border-color: #3b82f6;
      box-shadow: 0 0 0 3px rgba(59, 130, 246, 0.2);
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 25px;
      box-shadow: 0 1px 3px rgba(0, 0, 0, 0.1);
      border-radius: 8px;
      overflow: hidden;
    }
    th, td {
      border: 1px solid #e2e8f0;
      padding: 12px 15px;
      text-align: left;
    }
    th {
      background-color: #1e40af;
      color: white;
      font-weight: 500;
    }
    tr:nth-child(even) {
      background-color: #f8fafc;
    }
    tr:hover {
      background-color: #ebf4ff;
    }
    input[type="text"], input[type="number"], input[type="date"] {
      padding: 10px 12px;
      margin: 8px 0;
      width: 100%;
      border: 1px solid #cbd5e0;
      border-radius: 6px;
      transition: all 0.3s ease;
    }
    input:focus {
      outline: none;
      border-color: #3b82f6;
      box-shadow: 0 0 0 3px rgba(59, 130, 246, 0.2);
    }
    .form-row {
      margin-bottom: 20px;
    }
    .section-title {
      font-size: 1.1rem;
      margin: 20px 0 10px;
      color: #1e40af;
      font-weight: 500;
      display: block;
    }
    canvas {
      max-width: 100%;
      margin-top: 30px;
    }
    button {
      background: linear-gradient(to bottom, #3b82f6, #1d4ed8);
      color: white;
      border: none;
      padding: 12px 25px;
      cursor: pointer;
      border-radius: 8px;
      transition: all 0.3s ease;
      font-weight: 500;
      margin-top: 10px;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    }
    button:hover {
      background: linear-gradient(to bottom, #2563eb, #1e40af);
      transform: translateY(-2px);
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.15);
    }
    #listaAnotacoes {
      margin-top: 20px;
    }
    #listaAnotacoes div {
      background-color: white;
      padding: 15px;
      margin-bottom: 10px;
      border-radius: 8px;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.05);
      border-left: 3px solid #3b82f6;
    }
    #resultadoFinanceiro {
      margin-top: 20px;
      padding: 15px;
      background-color: #f0f9ff;
      border-radius: 8px;
      border-left: 4px solid #3b82f6;
      font-size: 1.2rem;
      color: #1e40af;
    }
    #alertaMensagens {
      padding: 15px;
      background-color: #fff7ed;
      border-radius: 8px;
      border-left: 4px solid #f97316;
      margin-top: 15px;
    }
    h2 {
      color: #1e3a8a;
      margin-bottom: 20px;
      font-weight: 600;
      font-size: 1.8rem;
      border-bottom: 2px solid #dbeafe;
      padding-bottom: 10px;
    }
    h3 {
      color: #1e3a8a;
      margin: 30px 0 15px;
      font-weight: 500;
      font-size: 1.4rem;
    }
  </style>
</head>
<body>
  <header>
    <img src="https://upload.wikimedia.org/wikipedia/commons/4/4c/Marca_IFET_vertical.png" alt="Logo IF">
    <h1>Painel de Controle Hidropônico</h1>
  </header>

  <nav>
    <button onclick="showTab('dashboard')"><i class="fas fa-tachometer-alt"></i> Dashboard</button>
    <button onclick="showTab('agenda')"><i class="fas fa-calendar-alt"></i> Agenda</button>
    <button onclick="showTab('anotacoes')"><i class="fas fa-clipboard"></i> Anotações</button>
    <button onclick="showTab('financeiro')"><i class="fas fa-chart-line"></i> Financeiro</button>
    <button onclick="showTab('alertas')"><i class="fas fa-bell"></i> Alertas</button>
  </nav>

  
  <div id="dashboard" class="tab active">
    <h2><i class="fas fa-tachometer-alt"></i> Monitoramento de Sensores</h2>
    <div class="dashboard">
      <div class="card">
        <div class="label"><i class="fas fa-water"></i> Nível de pH</div>
        <div id="ph" class="value">7.2</div>
      </div>
      <div class="card">
        <div class="label"><i class="fas fa-bolt"></i> Condutividade</div>
        <div id="condutividade" class="value">1.8 mS/cm</div>
      </div>
      <div class="card">
        <div class="label"><i class="fas fa-tint"></i> Umidade</div>
        <div id="umidade" class="value">65%</div>
      </div>
      <div class="card">
        <div class="label"><i class="fas fa-thermometer-half"></i> Temperatura</div>
        <div id="temperatura" class="value">24.5°C</div>
      </div>
      <div class="card">
        <div class="label"><i class="fas fa-vial"></i> Sólidos Totais</div>
        <div id="solidos" class="value">320 ppm</div>
      </div>
      <div class="card">
        <div class="label"><i class="fas fa-ruler-vertical"></i> Nível da Água</div>
        <div id="nivel" class="value">85%</div>
      </div>
      <div class="card">
        <div class="label"><i class="fas fa-power-off"></i> Status da Bomba</div>
        <div id="bomba" class="value">Ligada</div>
      </div>
    </div>
  </div>

  
  <div id="agenda" class="tab">
    <h2><i class="fas fa-calendar-alt"></i> Agenda de Cultivo</h2>
    <div class="form-row">
      <label for="dataPlantio" class="section-title">Data de Plantio</label>
      <input type="date" id="dataPlantio">
    </div>
    <div class="form-row">
      <label for="dataColheita" class="section-title">Data de Colheita</label>
      <input type="date" id="dataColheita">
    </div>
    <button onclick="adicionarAgenda()"><i class="fas fa-plus"></i> Adicionar à Agenda</button>
    <table id="tabelaAgenda">
      <thead>
        <tr>
          <th>Data de Plantio</th>
          <th>Data de Colheita</th>
          <th>Ações</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>2023-05-10</td>
          <td>2023-07-15</td>
          <td><button class="small-btn" onclick="removerLinha(this)">Remover</button></td>
        </tr>
        <tr>
          <td>2023-06-20</td>
          <td>2023-08-25</td>
          <td><button class="small-btn" onclick="removerLinha(this)">Remover</button></td>
        </tr>
      </tbody>
    </table>
  </div>

  
  <div id="anotacoes" class="tab">
    <h2><i class="fas fa-clipboard"></i> Anotações sobre o Cultivo</h2>
    <textarea id="notasCultivo" placeholder="Escreva suas anotações aqui..."></textarea>
    <button onclick="salvarAnotacao()"><i class="fas fa-save"></i> Salvar Anotação</button>
    <div id="listaAnotacoes">
      <div>Primeira colheita de alface hidropônica foi um sucesso! Rendimento de 15kg/m².</div>
      <div>Adicionar mais nutrientes na próxima semana conforme recomendação do fabricante.</div>
    </div>
  </div>

  
  <div id="financeiro" class="tab">
    <h2><i class="fas fa-chart-line"></i> Controle Financeiro</h2>
    <div class="form-row">
      <label for="investimento" class="section-title">Investimento Inicial (R$)</label>
      <input type="number" id="investimento" placeholder="Valor investido" step="0.01">
    </div>
    <div class="form-row">
      <label for="insumos" class="section-title">Gastos com Insumos (R$)</label>
      <input type="number" id="insumos" placeholder="Valor gasto com insumos" step="0.01">
    </div>
    <div class="form-row">
      <label for="maoDeObra" class="section-title">Gastos com Mão de Obra (R$)</label>
      <input type="number" id="maoDeObra" placeholder="Valor gasto com mão de obra" step="0.01">
    </div>
    <div class="form-row">
      <label for="energia" class="section-title">Gastos com Energia (R$)</label>
      <input type="number" id="energia" placeholder="Valor gasto com energia" step="0.01">
    </div>
    <div class="form-row">
      <label for="outros" class="section-title">Outros Custos (R$)</label>
      <input type="number" id="outros" placeholder="Outros custos" step="0.01">
    </div>
    <button onclick="calcularLucro()"><i class="fas fa-calculator"></i> Calcular Lucro</button>
    <div id="resultadoFinanceiro">
      Preencha os dados acima e clique em "Calcular Lucro" para ver os resultados.
    </div>

    <h3><i class="fas fa-chart-bar"></i> Comparação das Safras</h3>
    <canvas id="graficoComparacao"></canvas>
  </div>

  
  <div id="alertas" class="tab">
    <h2><i class="fas fa-bell"></i> Alertas de Sistema</h2>
    <div id="alertaMensagens">
      <div class="alerta-item"><i class="fas fa-exclamation-triangle"></i> Atenção: Nível de pH está acima do recomendado (7.2)</div>
      <div class="alerta-item"><i class="fas fa-info-circle"></i> Manutenção preventiva agendada para 15/11/2023</div>
    </div>
  </div>

  <script>
    
    function showTab(id) {
      document.querySelectorAll('.tab').forEach(tab => tab.classList.remove('active'));
      document.getElementById(id).classList.add('active');
    }

   
    function adicionarAgenda() {
      const dataPlantio = document.getElementById('dataPlantio').value;
      const dataColheita = document.getElementById('dataColheita').value;

      if (!dataPlantio || !dataColheita) {
        alert('Por favor, preencha as datas de plantio e colheita.');
        return;
      }

      const tabelaAgenda = document.getElementById('tabelaAgenda').getElementsByTagName('tbody')[0];
      const novaLinha = tabelaAgenda.insertRow();
      novaLinha.innerHTML = `
        <td>${formatarData(dataPlantio)}</td>
        <td>${formatarData(dataColheita)}</td>
        <td><button class="small-btn" onclick="removerLinha(this)">Remover</button></td>
      `;
      
      
      
      document.getElementById('dataPlantio').value = '';
      document.getElementById('dataColheita').value = '';
    }

    
    function formatarData(data) {
      const [ano, mes, dia] = data.split('-');
      return ${dia}/${mes}/${ano};
    }

    
    function removerLinha(botao) {
      const linha = botao.closest('tr');
      linha.remove();
    }

    
    function salvarAnotacao() {
      const anotacao = document.getElementById('notasCultivo').value.trim();

      if (!anotacao) {
        alert('Por favor, escreva uma anotação.');
        return;
      }

      const listaAnotacoes = document.getElementById('listaAnotacoes');
      const novaNota = document.createElement('div');
      novaNota.textContent = anotacao;
      listaAnotacoes.prepend(novaNota);

      
      document.getElementById('notasCultivo').value = '';
    }

    
    function calcularLucro() {
      const investimento = parseFloat(document.getElementById('investimento').value) || 0;
      const insumos = parseFloat(document.getElementById('insumos').value) || 0;
      const maoDeObra = parseFloat(document.getElementById('maoDeObra').value) || 0;
      const energia = parseFloat(document.getElementById('energia').value) || 0;
      const outros = parseFloat(document.getElementById('outros').value) || 0;

      const totalGastos = insumos + maoDeObra + energia + outros;
      const lucro = investimento - totalGastos;
      
      const resultado = document.getElementById('resultadoFinanceiro');
      resultado.innerHTML = `
        <strong>Investimento Inicial:</strong> R$ ${investimento.toFixed(2)}<br>
        <strong>Total de Gastos:</strong> R$ ${totalGastos.toFixed(2)}<br>
        <strong>Lucro Estimado:</strong> <span style="color: ${lucro >= 0 ? '#1e40af' : '#dc2626'}; font-weight:600">R$ ${lucro.toFixed(2)}</span>
      `;

      
      adicionarSafraAoGrafico(lucro);
    }

    
    let safraCount = 0;
    const safraLucros = [1250.50, 980.75, 1500.00]; 

    
    function inicializarGrafico() {
      const ctx = document.getElementById('graficoComparacao').getContext('2d');
      window.graficoComparacao = new Chart(ctx, {
        type: 'bar',
        data: {
          labels: safraLucros.map((_, index) => Safra ${index + 1}),
          datasets: [{
            label: 'Lucro por Safra (R$)',
            data: safraLucros,
            backgroundColor: '#3b82f6',
            borderColor: '#1d4ed8',
            borderWidth: 1
          }]
        },
        options: {
          responsive: true,
          scales: {
            y: {
              beginAtZero: true,
              title: {
                display: true,
                text: 'Valor em R$'
              }
            },
            x: {
              title: {
                display: true,
                text: 'Safras'
              }
            }
          },
          plugins: {
            tooltip: {
              callbacks: {
                label: function(context) {
                  return R$ $ {context.raw.toFixed(2)};
                }
              }
            }
          }
        }
      });
    }

    
    function adicionarSafraAoGrafico(lucro) {
      safraLucros.push(lucro);
      
      if (window.graficoComparacao) {
        window.graficoComparacao.data.labels.push(Safra ${safraLucros.length});
        window.graficoComparacao.data.datasets[0].data = safraLucros;
        window.graficoComparacao.update();
      }
    }

    
    function atualizarSensores() {
      const sensores = ['ph', 'condutividade', 'umidade', 'temperatura', 'solidos', 'nivel', 'bomba'];
      const valores = {
        ph: (6.8 + Math.random() * 0.8).toFixed(1),
        condutividade: (1.5 + Math.random() * 0.6).toFixed(1) + ' mS/cm',
        umidade: (60 + Math.random() * 10).toFixed(0) + '%',
        temperatura: (22 + Math.random() * 5).toFixed(1) + '°C',
        solidos: (300 + Math.random() * 50).toFixed(0) + ' ppm',
        nivel: (80 + Math.random() * 10).toFixed(0) + '%',
        bomba: Math.random() > 0.5 ? 'Ligada' : 'Desligada'
      };
      
      sensores.forEach(sensor => {
        document.getElementById(sensor).textContent = valores[sensor];
      });
    }

    
    document.addEventListener('DOMContentLoaded', function() {
      inicializarGrafico();
      
    
      setInterval(atualizarSensores, 3000);
      atualizarSensores();
    });
  </script>
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
</body>
</html>