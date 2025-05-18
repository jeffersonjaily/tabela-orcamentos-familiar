### tabela-orcamentos-familiar

<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Controle de Orçamento Familiar</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
      background-color: #f5f5f5;
    }

    h2 {
      text-align: center;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      background: #fff;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    th, td {
      padding: 10px;
      text-align: center;
      border: 1px solid #ccc;
    }

    th {
      background-color: #e0e0e0;
    }

    .ganhos {
      background-color: #c8e6c9;
    }

    .despesas {
      background-color: #ffcdd2;
    }

    .total {
      font-weight: bold;
      background-color: #f0f0f0;
    }

    input[type="number"] {
      width: 60px;
    }

    .semana-wrapper input {
      margin: 2px;
      width: 55px;
    }
  </style>
</head>
<body>

  <h2>Tabela de Controle de Orçamento Familiar</h2>

  <table>
    <tr>
      <th colspan="2" class="ganhos">Receitas</th>
      <th>Recebida (R$)</th>
    </tr>
    <tbody id="receitas">
      <tr><td colspan="2">Salários</td><td><input type="number" class="receita" /></td></tr>
      <tr><td colspan="2">Receita Moto - 1ª Semana (Seg a Dom)</td><td>
        <input type="number" class="receita" placeholder="Seg" />
        <input type="number" class="receita" placeholder="Ter" />
        <input type="number" class="receita" placeholder="Qua" />
        <input type="number" class="receita" placeholder="Qui" />
        <input type="number" class="receita" placeholder="Sex" />
        <input type="number" class="receita" placeholder="Sab" />
        <input type="number" class="receita" placeholder="Dom" />
      </td></tr>
      <tr><td colspan="2">Receita Moto - 2ª Semana (Seg a Dom)</td><td>
        <input type="number" class="receita" placeholder="Seg" />
        <input type="number" class="receita" placeholder="Ter" />
        <input type="number" class="receita" placeholder="Qua" />
        <input type="number" class="receita" placeholder="Qui" />
        <input type="number" class="receita" placeholder="Sex" />
        <input type="number" class="receita" placeholder="Sab" />
        <input type="number" class="receita" placeholder="Dom" />
      </td></tr>
      <tr><td colspan="2">Receita Moto - 3ª Semana (Seg a Dom)</td><td>
        <input type="number" class="receita" placeholder="Seg" />
        <input type="number" class="receita" placeholder="Ter" />
        <input type="number" class="receita" placeholder="Qua" />
        <input type="number" class="receita" placeholder="Qui" />
        <input type="number" class="receita" placeholder="Sex" />
        <input type="number" class="receita" placeholder="Sab" />
        <input type="number" class="receita" placeholder="Dom" />
      </td></tr>
      <tr><td colspan="2">Receita Moto - 4ª Semana (Seg a Dom)</td><td>
        <input type="number" class="receita" placeholder="Seg" />
        <input type="number" class="receita" placeholder="Ter" />
        <input type="number" class="receita" placeholder="Qua" />
        <input type="number" class="receita" placeholder="Qui" />
        <input type="number" class="receita" placeholder="Sex" />
        <input type="number" class="receita" placeholder="Sab" />
        <input type="number" class="receita" placeholder="Dom" />
      </td></tr>
      <tr><td colspan="2">Receitas Extras</td><td><input type="number" class="receita" /></td></tr>
      <tr><td colspan="2">Outros</td><td><input type="number" class="receita" /></td></tr>
    </tbody>
    <tr class="total">
      <td colspan="2">Total de Receitas</td>
      <td id="totalReceitas">0</td>
    </tr>

    <tr>
      <th colspan="2" class="despesas">Despesas</th>
      <th>Gasto (R$)</th>
    </tr>
    <tbody id="despesas">
      <tr><td colspan="2">Aluguel</td><td><input type="number" class="despesa" /></td></tr>
      <tr><td colspan="2">Internet</td><td><input type="number" class="despesa" /></td></tr>
      <tr><td colspan="2">Telefone Marido</td><td><input type="number" class="despesa" /></td></tr>
      <tr><td colspan="2">Telefone Esposa</td><td><input type="number" class="despesa" /></td></tr>
      <tr><td colspan="2">Despesas - 1ª Semana (Seg a Dom)</td><td>
        <input type="number" class="despesa" placeholder="Seg" />
        <input type="number" class="despesa" placeholder="Ter" />
        <input type="number" class="despesa" placeholder="Qua" />
        <input type="number" class="despesa" placeholder="Qui" />
        <input type="number" class="despesa" placeholder="Sex" />
        <input type="number" class="despesa" placeholder="Sab" />
        <input type="number" class="despesa" placeholder="Dom" />
      </td></tr>
      <tr><td colspan="2">Despesas - 2ª Semana (Seg a Dom)</td><td>
        <input type="number" class="despesa" placeholder="Seg" />
        <input type="number" class="despesa" placeholder="Ter" />
        <input type="number" class="despesa" placeholder="Qua" />
        <input type="number" class="despesa" placeholder="Qui" />
        <input type="number" class="despesa" placeholder="Sex" />
        <input type="number" class="despesa" placeholder="Sab" />
        <input type="number" class="despesa" placeholder="Dom" />
      </td></tr>
      <tr><td colspan="2">Despesas - 3ª Semana (Seg a Dom)</td><td>
        <input type="number" class="despesa" placeholder="Seg" />
        <input type="number" class="despesa" placeholder="Ter" />
        <input type="number" class="despesa" placeholder="Qua" />
        <input type="number" class="despesa" placeholder="Qui" />
        <input type="number" class="despesa" placeholder="Sex" />
        <input type="number" class="despesa" placeholder="Sab" />
        <input type="number" class="despesa" placeholder="Dom" />
      </td></tr>
      <tr><td colspan="2">Despesas - 4ª Semana (Seg a Dom)</td><td>
        <input type="number" class="despesa" placeholder="Seg" />
        <input type="number" class="despesa" placeholder="Ter" />
        <input type="number" class="despesa" placeholder="Qua" />
        <input type="number" class="despesa" placeholder="Qui" />
        <input type="number" class="despesa" placeholder="Sex" />
        <input type="number" class="despesa" placeholder="Sab" />
        <input type="number" class="despesa" placeholder="Dom" />
      </td></tr>
      <tr><td colspan="2">Conta de Luz</td><td><input type="number" class="despesa" /></td></tr>
      <tr><td colspan="2">Supermercado</td><td><input type="number" class="despesa" /></td></tr>
      <tr><td colspan="2">Medicamentos</td><td><input type="number" class="despesa" /></td></tr>
      <tr><td colspan="2">Cartão de Crédito</td><td><input type="number" class="despesa" /></td></tr>
      <tr><td colspan="2">Outros (1° a 4° Semana)</td>
        <td>
          <div class="semana-wrapper">
            <input type="number" class="despesa" placeholder="1°" /> 
            <input type="number" class="despesa" placeholder="2°" />
            <input type="number" class="despesa" placeholder="3°" />
            <input type="number" class="despesa" placeholder="4°" />
          </div>
        </td>
      </tr>
    </tbody>
    <tr class="total">
      <td colspan="2">Total de Despesas</td>
      <td id="totalDespesas">0</td>
    </tr>
    <tr class="total">
      <td colspan="2">Resultado Final (Receitas - Despesas)</td>
      <td id="resultadoFinal">0</td>
    </tr>
  </table>

  <script>
    function calcularTotais() {
      const somar = (selector) => {
        let total = 0;
        document.querySelectorAll(selector).forEach(input => {
          const val = parseFloat(input.value);
          if (!isNaN(val)) total += val;
        });
        return total;
      };

      const totalReceitas = somar(".receita");
      const totalDespesas = somar(".despesa");
      const resultado = totalReceitas - totalDespesas;

      document.getElementById("totalReceitas").innerText = totalReceitas.toFixed(2);
      document.getElementById("totalDespesas").innerText = totalDespesas.toFixed(2);
      document.getElementById("resultadoFinal").innerText = resultado.toFixed(2);
    }

    document.querySelectorAll("input").forEach(input => {
      input.addEventListener("input", calcularTotais);
    });

    calcularTotais(); // inicializa ao carregar
  </script>

</body>
</html>
<!-- Adicione abaixo do <table> -->
<div style="text-align: center; margin-top: 20px;">
  <button onclick="salvarDados()">💾 Salvar Dados</button>
  <button onclick="carregarDados()">📂 Carregar Dados</button>
  <button onclick="limparDados()">🧹 Limpar Dados</button>
</div>

<script>
  function calcularTotais() {
    const somar = (selector) => {
      let total = 0;
      document.querySelectorAll(selector).forEach(input => {
        const val = parseFloat(input.value);
        if (!isNaN(val)) total += val;
      });
      return total;
    };

    const totalReceitas = somar(".receita");
    const totalDespesas = somar(".despesa");
    const resultado = totalReceitas - totalDespesas;

    document.getElementById("totalReceitas").innerText = totalReceitas.toFixed(2);
    document.getElementById("totalDespesas").innerText = totalDespesas.toFixed(2);
    document.getElementById("resultadoFinal").innerText = resultado.toFixed(2);
  }

  document.querySelectorAll("input").forEach(input => {
    input.addEventListener("input", calcularTotais);
  });

  function salvarDados() {
    const dados = {};
    document.querySelectorAll("input").forEach((input, index) => {
      dados[index] = input.value;
    });
    localStorage.setItem("orcamentoFamiliar", JSON.stringify(dados));
    alert("Dados salvos com sucesso!");
  }

  function carregarDados() {
    const dadosSalvos = JSON.parse(localStorage.getItem("orcamentoFamiliar"));
    if (dadosSalvos) {
      document.querySelectorAll("input").forEach((input, index) => {
        if (dadosSalvos[index] !== undefined) {
          input.value = dadosSalvos[index];
        }
      });
      calcularTotais();
      alert("Dados carregados com sucesso!");
    } else {
      alert("Nenhum dado salvo encontrado.");
    }
  }

  function limparDados() {
    if (confirm("Tem certeza que deseja limpar os dados salvos?")) {
      localStorage.removeItem("orcamentoFamiliar");
      document.querySelectorAll("input").forEach(input => input.value = "");
      calcularTotais();
      alert("Dados limpos com sucesso.");
    }
  }

  // Carregar automaticamente ao abrir
  window.addEventListener("load", carregarDados);
</script>
