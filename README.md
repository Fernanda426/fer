<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Documentos do Evento - Desafio das Redes</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        .section-title {
            background-color: #2563eb;
            color: white;
            padding: 10px 15px;
            border-radius: 5px;
            margin-bottom: 20px;
        }
        .document-card {
            border-left: 4px solid #2563eb;
            margin-bottom: 30px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 8px;
            text-align: left;
        }
        th {
            background-color: #f2f2f2;
        }
        @media print {
            .no-print {
                display: none;
            }
            .print-margin {
                margin-top: 30px;
            }
        }
    </style>
</head>
<body class="bg-gray-100 p-6">
    <div class="max-w-5xl mx-auto bg-white rounded-lg shadow-lg p-8">
        <header class="text-center mb-8">
            <h1 class="text-4xl font-bold text-blue-600">Desafio das Redes</h1>
            <p class="text-xl text-gray-600">Copa Escolar de Handebol e Voleibol</p>
            <div class="mt-4">
                <button onclick="window.print()" class="no-print bg-blue-600 text-white px-4 py-2 rounded-lg hover:bg-blue-700 transition">Imprimir Documentos</button>
            </div>
        </header>

        <!-- 1. Ficha de Inscrição -->
        <div class="document-card">
            <h2 class="section-title">1. Ficha de Inscrição</h2>
            <div class="p-6 bg-gray-50 rounded-lg">
                <form class="grid grid-cols-1 md:grid-cols-2 gap-6">
                    <div class="col-span-2 text-center">
                        <h3 class="text-xl font-semibold text-blue-700 mb-2">FICHA DE INSCRIÇÃO</h3>
                        <p class="text-gray-600">Desafio das Redes - Copa Escolar de Handebol e Voleibol</p>
                    </div>

                    <div>
                        <label class="block text-gray-700 mb-2">Nome Completo:</label>
                        <input type="text" class="w-full px-3 py-2 border rounded-lg">
                    </div>
                    
                    <div>
                        <label class="block text-gray-700 mb-2">Idade:</label>
                        <input type="number" class="w-full px-3 py-2 border rounded-lg">
                    </div>
                    
                    <div>
                        <label class="block text-gray-700 mb-2">Série/Turma:</label>
                        <input type="text" class="w-full px-3 py-2 border rounded-lg">
                    </div>
                    
                    <div>
                        <label class="block text-gray-700 mb-2">Telefone:</label>
                        <input type="tel" class="w-full px-3 py-2 border rounded-lg">
                    </div>
                    
                    <div>
                        <label class="block text-gray-700 mb-2">Modalidade:</label>
                        <select class="w-full px-3 py-2 border rounded-lg">
                            <option>Handebol</option>
                            <option>Voleibol</option>
                        </select>
                    </div>
                    
                    <div>
                        <label class="block text-gray-700 mb-2">Categoria:</label>
                        <select class="w-full px-3 py-2 border rounded-lg">
                            <option>Masculino</option>
                            <option>Feminino</option>
                            <option>Misto</option>
                        </select>
                    </div>
                    
                    <div class="col-span-2">
                        <label class="block text-gray-700 mb-2">Nome da Equipe:</label>
                        <input type="text" class="w-full px-3 py-2 border rounded-lg">
                    </div>
                    
                    <div class="col-span-2">
                        <label class="block text-gray-700 mb-2">Responsável Legal (para menores de idade):</label>
                        <input type="text" class="w-full px-3 py-2 border rounded-lg">
                    </div>
                    
                    <div class="col-span-2">
                        <label class="block text-gray-700 mb-2">Declaração:</label>
                        <p class="text-sm text-gray-600 bg-gray-100 p-3 rounded">Declaro que todas as informações fornecidas são verdadeiras e que estou ciente das regras do evento. Autorizo o uso de minha imagem para fins de divulgação do evento.</p>
                    </div>
                    
                    <div>
                        <label class="block text-gray-700 mb-2">Assinatura do Participante:</label>
                        <div class="border-t border-gray-400 h-12"></div>
                    </div>
                    
                    <div>
                        <label class="block text-gray-700 mb-2">Data:</label>
                        <div class="border-t border-gray-400 h-12"></div>
                    </div>
                </form>
            </div>
        </div>

        <!-- 2. Regulamento do Evento -->
        <div class="document-card print-margin">
            <h2 class="section-title">2. Regulamento do Evento</h2>
            <div class="p-6 bg-gray-50 rounded-lg">
                <h3 class="text-xl font-semibold text-blue-700 mb-4">REGULAMENTO OFICIAL</h3>
                
                <div class="mb-6">
                    <h4 class="font-bold text-lg mb-2">1. DISPOSIÇÕES PRELIMINARES</h4>
                    <p class="text-gray-700 mb-4">1.1 O "Desafio das Redes" é um evento esportivo escolar promovido pela Escola Secundária XYZ, com competições de Handebol e Voleibol.</p>
                    <p class="text-gray-700">1.2 O objetivo principal do evento é promover a integração entre os alunos por meio do esporte.</p>
                </div>
                
                <div class="mb-6">
                    <h4 class="font-bold text-lg mb-2">2. DA PARTICIPAÇÃO</h4>
                    <p class="text-gray-700 mb-2">2.1 Poderão participar alunos regularmente matriculados na Escola Secundária XYZ.</p>
                    <p class="text-gray-700 mb-2">2.2 Cada equipe deve ter no mínimo 7 e no máximo 12 jogadores (Handebol) ou 6 e no máximo 12 jogadores (Voleibol).</p>
                    <p class="text-gray-700">2.3 Todos os participantes devem apresentar documento de identificação no credenciamento.</p>
                </div>
                
                <div class="mb-6">
                    <h4 class="font-bold text-lg mb-2">3. DAS MODALIDADES</h4>
                    <h5 class="font-bold mb-1">3.1 Handebol</h5>
                    <ul class="list-disc pl-5 mb-3">
                        <li class="text-gray-700">Tempo de jogo: 2 tempos de 10 minutos com intervalo de 5 minutos</li>
                        <li class="text-gray-700">Sistema de disputa: Eliminatório simples</li>
                        <li class="text-gray-700">Regras oficiais da CBHb com adaptações para espaço escolar</li>
                    </ul>
                    <h5 class="font-bold mb-1">3.2 Voleibol</h5>
                    <ul class="list-disc pl-5">
                        <li class="text-gray-700">Sets de 15 pontos (máximo de 3 sets)</li>
                        <li class="text-gray-700">Sistema de disputa: Rodízio na fase inicial e eliminatório na fase final</li>
                        <li class="text-gray-700">Regras adaptadas da CBV para categorias escolares</li>
                    </ul>
                </div>
                
                <div class="mb-6">
                    <h4 class="font-bold text-lg mb-2">4. DOS JOGOS</h4>
                    <p class="text-gray-700 mb-2">4.1 O cronograma de jogos será divulgado no dia 16/03/2024.</p>
                    <p class="text-gray-700 mb-2">4.2 O atraso superior a 10 minutos resultará em W.O. (vitória do adversário).</p>
                    <p class="text-gray-700">4.3 Em caso de empate (Handebol), haverá disputa de pênaltis (5 cobranças).</p>
                </div>
                
                <div class="mb-6">
                    <h4 class="font-bold text-lg mb-2">5. DAS PENALIDADES</h4>
                    <p class="text-gray-700 mb-2">5.1 Comportamentos antidesportivos serão punidos com cartão amarelo (advertência) ou vermelho (expulsão).</p>
                    <p class="text-gray-700">5.2 Agressões físicas ou verbais resultarão em desclassificação da equipe.</p>
                </div>
                
                <div class="mb-6">
                    <h4 class="font-bold text-lg mb-2">6. DISPOSIÇÕES FINAIS</h4>
                    <p class="text-gray-700 mb-2">6.1 Casos omissos serão resolvidos pela comissão organizadora.</p>
                    <p class="text-gray-700">6.2 A participação no evento implica na aceitação deste regulamento.</p>
                </div>
                
                <div class="mt-8 text-right">
                    <p class="text-gray-700">Escola Secundária XYZ, 01 de março de 2024.</p>
                    <p class="font-semibold mt-4">Comissão Organizadora do Desafio das Redes</p>
                </div>
            </div>
        </div>

        <!-- 3. Súmula de Jogos -->
        <div class="document-card print-margin">
            <h2 class="section-title">3. Súmula de Jogos</h2>
            <div class="p-6 bg-gray-50 rounded-lg">
                <h3 class="text-xl font-semibold text-blue-700 mb-4">SÚMULA DE JOGO - DESAFIO DAS REDES</h3>
                
                <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-6">
                    <div>
                        <p><span class="font-semibold">Modalidade:</span> <span class="ml-2 border-b border-gray-400 inline-block min-w-[150px]">Handebol/Voleibol</span></p>
                        <p class="mt-2"><span class="font-semibold">Categoria:</span> <span class="ml-2 border-b border-gray-400 inline-block min-w-[150px]">Masculino/Feminino/Misto</span></p>
                    </div>
                    <div>
                        <p><span class="font-semibold">Data:</span> <span class="ml-2 border-b border-gray-400 inline-block min-w-[150px]"></span></p>
                        <p class="mt-2"><span class="font-semibold">Horário:</span> <span class="ml-2 border-b border-gray-400 inline-block min-w-[150px]"></span></p>
                    </div>
                </div>

                <div class="mb-6">
                    <table>
                        <thead>
                            <tr>
                                <th>Equipe 1</th>
                                <th>Placar</th>
                                <th>Equipe 2</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td class="text-center"><input type="text" class="w-full px-2 py-1 border-none"></td>
                                <td class="text-center"><input type="text" class="w-16 px-2 py-1 border mx-auto text-center"></td>
                                <td class="text-center"><input type="text" class="w-full px-2 py-1 border-none"></td>
                            </tr>
                        </tbody>
                    </table>
                </div>

                <div class="mb-6">
                    <h4 class="font-bold text-lg mb-2">Arbitragem:</h4>
                    <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
                        <div>
                            <label class="block text-gray-700 mb-1">Árbitro Principal:</label>
                            <input type="text" class="w-full px-2 py-1 border rounded">
                        </div>
                        <div>
                            <label class="block text-gray-700 mb-1">Árbitro Auxiliar:</label>
                            <input type="text" class="w-full px-2 py-1 border rounded">
                        </div>
                        <div>
                            <label class="block text-gray-700 mb-1">Anotador:</label>
                            <input type="text" class="w-full px-2 py-1 border rounded">
                        </div>
                    </div>
                </div>

                <div class="mb-6">
                    <h4 class="font-bold text-lg mb-2">Ocorrências:</h4>
                    <textarea class="w-full px-3 py-2 border rounded-lg h-24" placeholder="Registrar aqui cartões, incidentes, substituições..."></textarea>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                    <div>
                        <label class="block text-gray-700 mb-1">Assinatura Capitão Equipe 1:</label>
                        <div class="border-t border-gray-400 h-12"></div>
                    </div>
                    <div>
                        <label class="block text-gray-700 mb-1">Assinatura Capitão Equipe 2:</label>
                        <div class="border-t border-gray-400 h-12"></div>
                    </div>
                </div>

                <div class="mt-6">
                    <label class="block text-gray-700 mb-1">Assinatura Árbitro Principal:</label>
                    <div class="border-t border-gray-400 h-12"></div>
                </div>
            </div>
        </div>

        <!-- 4. Modelo de Cronograma Visual -->
        <div class="document-card print-margin">
            <h2 class="section-title">4. Modelo de Cronograma Visual</h2>
            <div class="p-6 bg-gray-50 rounded-lg">
                <h3 class="text-xl font-semibold text-blue-700 mb-4">CRONOGRAMA DO EVENTO - DESAFIO DAS REDES</h3>
                
                <div class="mb-6">
                    <h4 class="font-bold text-lg mb-2">Período de Inscrições: 01/03 a 15/03/2024</h4>
                </div>

                <div class="overflow-x-auto">
                    <table class="min-w-full">
                        <thead>
                            <tr class="bg-blue-600 text-white">
                                <th class="px-4 py-2">Horário</th>
                                <th class="px-4 py-2">20/03 - Manhã</th>
                                <th class="px-4 py-2">20/03 - Tarde</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td class="px-4 py-2 font-semibold border">8:00 - 9:00</td>
                                <td class="px-4 py-2 border" colspan="2">Credenciamento das Equipes</td>
                            </tr>
                            <tr class="bg-gray-50">
                                <td class="px-4 py-2 font-semibold border">9:00 - 9:30</td>
                                <td class="px-4 py-2 border" colspan="2">Cerimônia de Abertura</td>
                            </tr>
                            <tr>
                                <td class="px-4 py-2 font-semibold border">9:30 - 10:00</td>
                                <td class="px-4 py-2 border bg-green-100">Handebol - Fase de Grupos (Quadra A)</td>
                                <td class="px-4 py-2 border"></td>
                            </tr>
                            <tr class="bg-gray-50">
                                <td class="px-4 py-2 font-semibold border">10:00 - 10:30</td>
                                <td class="px-4 py-2 border bg-green-100">Handebol - Fase de Grupos (Quadra B)</td>
                                <td class="px-4 py-2 border"></td>
                            </tr>
                            <tr>
                                <td class="px-4 py-2 font-semibold border">10:30 - 11:00</td>
                                <td class="px-4 py-2 border bg-green-100">Handebol - Quartas de Final</td>
                                <td class="px-4 py-2 border"></td>
                            
