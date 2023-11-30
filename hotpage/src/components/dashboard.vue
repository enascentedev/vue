<template>
	<div class="overflow-x-auto p-3.5">
    <table class="min-w-full bg-white">
      <thead class="bg-gray-800 text-white">
        <tr>
          <th class="text-left py-3 px-4 uppercase font-semibold text-sm">Nome</th>
          <th class="text-left py-3 px-4 uppercase font-semibold text-sm">Cargo</th>
          <th class="text-left py-3 px-4 uppercase font-semibold text-sm">Cidade</th>
          <th class="text-left py-3 px-4 uppercase font-semibold text-sm">Idade</th>
          <th class="text-left py-3 px-4 uppercase font-semibold text-sm">Data de Início</th>
          
          <th class="text-left py-3 px-4 uppercase font-semibold text-sm">Salário</th>
        </tr>
      </thead>
      <tbody class="text-gray-700">
        <!-- Repita para cada linha -->
        <tr>
          <td class="text-left py-3 px-4">Emanuel Nascente</td>
          <td class="text-left py-3 px-4">Desenvolvedor Júnior</td>
          <td class="text-left py-3 px-4">Porto Alegre</td>
          <td class="text-left py-3 px-4">33</td>
          <td class="text-left py-3 px-4">28/11/2008</td>
          <td class="w-10 text-left py-3 px-4">$</td>
        </tr>
        <!-- ... outras linhas -->
      </tbody>
    </table>
  </div>

</template>

<script>
export default {
	name: "Dashboard",
};
</script>
