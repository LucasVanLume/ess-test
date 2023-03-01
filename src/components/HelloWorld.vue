<template>
  <div>
    <div>
      <div class="md:grid md:grid-cols-7 md:gap-5">
        <div class="md:col-start-2 md:col-span-4 mt-5 md:mt-0">
          <form action="#" method="POST">
            <div class="flex justify-center items-center">
              <div class="shadow sm:overflow-hidden sm:rounded-md w-full">
                <div class="space-y-6 bg-gray-50 px-4 py-5 sm:p-6">
                  <br>
                  <div class="grid grid-cols-11 gap-6">
                    <div class="col-span-11 sm:col-start-2 sm:col-span-4">
                      <h2 class="text-4xl font-bold leading-10 text-gray-800">Responsável da loja</h2>
                    </div>
                    <div class="col-span-11 sm:col-start-7 sm:col-span-4">
                      <p class="mt-1 text-sm text-gray-700">Informe os dados da pessoa que tem o nome no contrato social da empresa.</p>
                    </div>
                  </div>
                  <br>
                  <br>
                  <div class="grid grid-cols-11 gap-6">                     
                    <div class="col-span-11 sm:col-start-2 sm:col-span-9">
                      <label for="name" class="block uppercase tracking-wide text-gray-700 text-xs font-bold mb-2">Nome completo</label>
                      <input type="text" name="name" id="name" autocomplete="name" class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" />
                    </div>

                    <div class="col-span-11 sm:col-start-2 sm:col-span-4">
                      <label for="cpf" class="block uppercase tracking-wide text-gray-700 text-xs font-bold mb-2">CPF</label>
                      <input type="text" name="cpf" id="cpf" autocomplete="tax-id-number" class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" placeholder="174.494.513-08"/>
                    </div>

                    <div class="col-span-11 sm:col-start-7 sm:col-span-4">
                      <label for="rg" class="block uppercase tracking-wide text-gray-700 text-xs font-bold mb-2">RG</label>
                      <input type="text" name="rg" id="rg" autocomplete="government-issued-id" class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" placeholder="3.007.954"/>
                    </div>

                    <div class="col-span-11 sm:col-start-2 sm:col-span-9">
                      <div class="py-5">
                        <div class="border-t border-black" />
                      </div>
                    </div>                    
                  </div>
<!--///////////////////////////////////////////////////-->
                  
                  <div class="grid grid-cols-11 gap-6">
                    <div class="col-span-11 sm:col-start-2 sm:col-span-4">
                      <h2 class="text-4xl font-bold leading-10 text-gray-800">Informações da loja</h2>
                    </div>
                    <div class="col-span-11 sm:col-start-7 sm:col-span-4">
                      <p class="mt-1 text-sm text-gray-700">Preencha com os dados do seu negócio.</p>
                    </div>
                  </div>
                  <br>
                  <br>
                  <div class="grid grid-cols-11 gap-6">                     
                    <div class="col-span-11 sm:col-start-2 sm:col-span-4">
                      <label for="cnpj" class="block uppercase tracking-wide text-gray-700 text-xs font-bold mb-2">CNPJ</label>
                      <input type="text" name="cnpj" id="cnpj" autocomplete="organization-tax-id" class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" placeholder="12.345.678/0001-00"/>
                    </div>

                    <div class="col-span-11 sm:col-start-7 sm:col-span-4">
                      <label for="razao-social" class="block uppercase tracking-wide text-gray-700 text-xs font-bold mb-2">Razão social</label>
                      <input type="text" name="razao-social" id="razao-social" autocomplete="organization" class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" placeholder="Marcelinho LTDA"/>
                    </div>

                    <div class="col-span-11 sm:col-start-2 sm:col-span-4">
                      <label for="nome-loja" class="block uppercase tracking-wide text-gray-700 text-xs font-bold mb-2">Nome da loja</label>
                      <input type="text" name="nome-loja" id="nome-loja" autocomplete="organization" class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline"/>
                    </div>

                    <div class="col-span-11 sm:col-start-7 sm:col-span-4">
                      <label for="telefone" class="block uppercase tracking-wide text-gray-700 text-xs font-bold mb-2">Telefone ou celular da loja</label>
                      <input type="tel" name="telefone" id="telefone" autocomplete="tel" class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" placeholder="(81)983462832"/>
                    </div>

                    <div class="col-span-11 sm:col-start-4 sm:col-span-5">
                      <label for="especialidade" class="block uppercase tracking-wide text-gray-700 text-xs font-bold mb-2">Especialidade</label>
                      <input type="text" name="especialidade" id="especialidade" autocomplete="food" class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" placeholder="Vegana"/>
                    </div>

                    <div class="col-span-11 sm:col-start-2 sm:col-span-9">
                      <div class="py-5">
                        <div class="border-t border-black" />
                      </div>
                    </div>                    
                  </div>


<!--///////////////////////////////////////////////////-->
                  
                  <div class="grid grid-cols-11 gap-6">
                    <div class="col-span-11 sm:col-start-2 sm:col-span-4">
                      <h2 class="text-4xl font-bold leading-10 text-gray-800">Endereço da loja</h2>
                    </div>
                    <div class="col-span-11 sm:col-start-7 sm:col-span-4">
                      <p class="mt-1 text-sm text-gray-700">Preencha com as informações de endereço da sua loja.</p>
                    </div>
                  </div>
                  <br>
                  <br>
                  <div class="grid grid-cols-11 gap-6">                     
                    <div class="col-span-11 sm:col-start-2 sm:col-span-4">
                      <label for="cep" class="block uppercase tracking-wide text-gray-700 text-xs font-bold mb-2">CEP</label>
                      <input type="text" name="cep" id="cep" autocomplete="postal-code" class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" placeholder="74938-034"/>
                    </div>

                    <div class="col-span-11 sm:col-start-7 sm:col-span-4">
                      <label for="estado-uf" class="block uppercase tracking-wide text-gray-700 text-xs font-bold mb-2">UF</label>
                      <select id="estado-uf" name="estado-uf" autocomplete="address-level1" class="shadow border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline">
                        <option value="NONE">---</option>
                        <option value="AC">Acre</option>
                        <option value="AL">Alagoas</option>
                        <option value="AP">Amapá</option>
                        <option value="AM">Amazonas</option>
                        <option value="BA">Bahia</option>
                        <option value="CE">Ceará</option>
                        <option value="DF">Distrito Federal</option>
                        <option value="ES">Espírito Santo</option>
                        <option value="GO">Goiás</option>
                        <option value="MA">Maranhão</option>
                        <option value="MT">Mato Grosso</option>
                        <option value="MS">Mato Grosso do Sul</option>
                        <option value="MG">Minas Gerais</option>
                        <option value="PA">Pará</option>
                        <option value="PB">Paraíba</option>
                        <option value="PR">Paraná</option>
                        <option value="PE">Pernambuco</option>
                        <option value="PI">Piauí</option>
                        <option value="RJ">Rio de Janeiro</option>
                        <option value="RN">Rio Grande do Norte</option>
                        <option value="RS">Rio Grande do Sul</option>
                        <option value="RO">Rondônia</option>
                        <option value="RR">Roraima</option>
                        <option value="SC">Santa Catarina</option>
                        <option value="SP">São Paulo</option>
                        <option value="SE">Sergipe</option>
                        <option value="TO">Tocantins</option>
                      </select>
                    </div>

                    <div class="col-span-11 sm:col-start-2 sm:col-span-4">
                      <label for="cidade" class="block uppercase tracking-wide text-gray-700 text-xs font-bold mb-2">Cidade</label>
                      <input type="text" name="cidade" id="cidade" autocomplete="address-level2" class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline"/>
                    </div>

                    <div class="col-span-11 sm:col-start-7 sm:col-span-4">
                      <label for="bairro" class="block uppercase tracking-wide text-gray-700 text-xs font-bold mb-2">Bairro</label>
                      <input type="text" name="bairro" id="bairro" autocomplete="neighborhood" class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline"/>
                    </div>

                    <div class="col-span-11 sm:col-start-2 sm:col-span-9">
                      <label for="endereoo" class="block uppercase tracking-wide text-gray-700 text-xs font-bold mb-2">Endereço</label>
                      <input type="text" name="endereco" id="endereco" autocomplete="street-address" class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline"/>
                    </div>

                    <div class="col-span-11 sm:col-start-2 sm:col-span-4">
                      <label for="numero" class="block uppercase tracking-wide text-gray-700 text-xs font-bold mb-2">Número</label>
                      <input type="number" name="numero" id="numero" autocomplete="address-number" class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline"/>
                    </div>

                    <div class="col-span-11 sm:col-start-7 sm:col-span-4">
                      <label for="complemento" class="block uppercase tracking-wide text-gray-700 text-xs font-bold mb-2">Complemento (opcional)</label>
                      <input type="text" name="complemento" id="complemento" autocomplete="off" class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline"/>
                    </div>
                   
                  </div>             
                </div>
                <div class="bg-gray-200 px-4 py-3 text-right sm:px-6">
                  <button type="submit" class="inline-flex justify-center rounded-md border border-transparent bg-indigo-600 py-2 px-4 text-sm font-medium text-white shadow-sm hover:bg-indigo-700 focus:outline-none focus:ring-2 focus:ring-indigo-500 focus:ring-offset-2">Salvar</button>
                </div>
              </div>
            </div>
            <br>
          </form>
        </div>
      </div>
    </div>    
  </div>
</template>

<script scoped>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>
