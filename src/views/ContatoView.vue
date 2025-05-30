<template>
  <div class="m-12 flex items-center justify-center p-4">

    <div class="bg-white rounded-2xl shadow-lg w-full max-w-2xl">

      <div class="p-8">
        <h2 class="text-2xl font-semibold mb-6 text-gray-800">Entre em Contato</h2>
        
        <form class="space-y-4">
          <div>
            <label class="block text-sm font-medium text-gray-700 mb-1">Nome</label>
            <input type="text" placeholder="Digite seu nome" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:outline-none">
          </div>

          <div>
            <label class="block text-sm font-medium text-gray-700 mb-1">Email para contato</label>
            <input type="text" placeholder="Digite seu email" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:outline-none">
          </div>

          <div>
            <label class="block text-sm font-medium text-gray-700 mb-1">Mensagem</label>
            <textarea placeholder="Digite sua mensagem" class="w-full p-2 border border-gray-300 rounded-md focus:outline-none" rows="4"></textarea>
          </div>

          <button class="w-full bg-blue-700 text-white py-2 rounded-md hover:bg-blue-900 transition duration-200">
            Entrar
          </button>
        </form>
      </div>

    </div>
    
  </div>
</template>
