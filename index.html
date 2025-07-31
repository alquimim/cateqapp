<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CateqApp</title>
    <!-- Carrega o Tailwind CSS via CDN para estilização -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Carrega a fonte Inter do Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    <style>
        /* Define a fonte Inter como padrão para todo o corpo da página */
        body {
            font-family: 'Inter', sans-serif;
            /* Aplica a cor de fundo principal 'Bege Claro/Areia' (#F5DEB3) */
            background-color: #F5DEB3;
            display: flex;
            justify-content: center;
            align-items: flex-start; /* Alinha ao topo para permitir rolagem se o conteúdo for grande */
            min-height: 100vh; /* Garante que o corpo ocupe pelo menos a altura da viewport */
            padding: 20px; /* Adiciona um padding geral para o conteúdo não colar nas bordas */
            box-sizing: border-box; /* Inclui padding na largura/altura total */
        }

        /* Estilo para o logo CateqApp, mesclando as cores */
        .cateqapp-logo {
            font-size: 3rem; /* Tamanho da fonte */
            font-weight: 800; /* Negrito */
            text-align: center; /* Centraliza o texto */
            /* Aplica um gradiente de texto usando as cores da identidade visual */
            background: linear-gradient(to right, #CC0000, #D2B48C);
            -webkit-background-clip: text; /* Recorta o fundo para o texto */
            -webkit-text-fill-color: transparent; /* Torna o texto transparente para mostrar o fundo */
            color: #CC0000; /* Cor de fallback caso o gradiente não seja suportado */
        }

        /* Estilo para o iframe do Google Forms para ser responsivo */
        .google-forms-iframe {
            width: 100%;
            height: 80vh; /* Ocupa 80% da altura da viewport */
            border: none;
            border-radius: 0.75rem; /* rounded-lg */
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05); /* shadow-lg */
        }

        /* Estilo para esconder páginas */
        .hidden-page {
            display: none;
        }

        /* Estilo para o contêiner principal do aplicativo */
        .app-container {
            background-color: #FFFFFF; /* Fundo branco puro */
            border-radius: 1rem; /* Cantos mais arredondados para o contêiner principal */
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 8px 10px -6px rgba(0, 0, 0, 0.1); /* Sombra mais proeminente */
            padding: 2.5rem; /* Padding interno generoso */
            max-width: 90%; /* Largura máxima para telas maiores */
            width: 100%; /* Ocupa a largura total disponível */
            margin-top: 20px; /* Espaçamento do topo */
            margin-bottom: 20px; /* Espaçamento da base */
            box-sizing: border-box;
        }

        /* Ajustes responsivos para o contêiner principal */
        @media (min-width: 768px) {
            .app-container {
                max-width: 768px; /* Largura máxima para tablets */
            }
        }
        @media (min-width: 1024px) {
            .app-container {
                max-width: 900px; /* Largura máxima para desktops */
            }
        }

    </style>
</head>
<body>
    <!-- Contêiner principal do aplicativo -->
    <div id="app-container" class="app-container">

        <!-- Página de Boas-Vindas -->
        <div id="welcome-page" class="page">
            <h1 class="cateqapp-logo mb-6">CateqApp</h1>
            <p class="text-center text-gray-700 mb-8 text-lg leading-relaxed">
                O CateqApp simplifica a gestão de turmas e o registro de presença para catequistas e coordenadores.
                Centralize informações, acompanhe encontros e dedique mais tempo à formação espiritual.
                Sua ferramenta digital intuitiva para a catequese.
            </p>
            <div class="flex justify-center">
                <button onclick="showPage('communities-page')"
                        class="bg-[#CC0000] hover:bg-red-700 text-white font-semibold py-3 px-8 rounded-lg shadow-lg
                               transition-colors duration-300 transform hover:scale-105 focus:outline-none focus:ring-4 focus:ring-red-300">
                    Registrar Presença
                </button>
            </div>
        </div>

        <!-- Página de Comunidades -->
        <div id="communities-page" class="page hidden-page">
            <h2 class="text-[#333333] text-3xl font-bold mb-8 text-center">Comunidades</h2>
            <div class="flex flex-col space-y-4 md:space-y-0 md:flex-row md:space-x-4 justify-center">
                <button onclick="showTurmas('Matriz')"
                        class="bg-[#CC0000] hover:bg-red-700 text-white font-semibold py-3 px-6 rounded-lg shadow-md
                               transition-colors duration-300 transform hover:scale-105 focus:outline-none focus:ring-4 focus:ring-red-300 w-full md:flex-1">
                    Matriz
                </button>
                <button onclick="showTurmas('Santa Filomena')"
                        class="bg-[#CC0000] hover:bg-red-700 text-white font-semibold py-3 px-6 rounded-lg shadow-md
                               transition-colors duration-300 transform hover:scale-105 focus:outline-none focus:ring-4 focus:ring-red-300 w-full md:flex-1">
                    Santa Filomena
                </button>
                <button onclick="showTurmas('Nossa Senhora de Fátima')"
                        class="bg-[#CC0000] hover:bg-red-700 text-white font-semibold py-3 px-6 rounded-lg shadow-md
                               transition-colors duration-300 transform hover:scale-105 focus:outline-none focus:ring-4 focus:ring-red-300 w-full md:flex-1">
                    Nossa Senhora de Fátima
                </button>
            </div>
            <div class="flex justify-center mt-8">
                <button onclick="showPage('welcome-page')"
                        class="bg-gray-400 hover:bg-gray-500 text-white font-semibold py-2 px-6 rounded-lg shadow-sm
                               transition-colors duration-300 focus:outline-none focus:ring-4 focus:ring-gray-300">
                    Voltar
                </button>
            </div>
        </div>

        <!-- Página de Turmas -->
        <div id="turmas-page" class="page hidden-page">
            <h2 id="turmas-title" class="text-[#333333] text-3xl font-bold mb-8 text-center">Turmas da Comunidade</h2>
            <div id="turmas-list" class="flex flex-col gap-6 mb-8">
                <!-- Categorias e Cards das turmas serão injetados aqui via JavaScript -->
            </div>
            <div id="google-forms-embed" class="hidden-page">
                <iframe id="forms-iframe" class="google-forms-iframe" src="" frameborder="0" marginheight="0" marginwidth="0">Carregando…</iframe>
            </div>
            <div class="flex justify-center mt-8">
                <button onclick="showPage('communities-page'); hideFormsIframe();"
                        class="bg-gray-400 hover:bg-gray-500 text-white font-semibold py-2 px-6 rounded-lg shadow-sm
                               transition-colors duration-300 focus:outline-none focus:ring-4 focus:ring-gray-300">
                    Voltar
                </button>
            </div>
        </div>

    </div>

    <script>
        // Dados das comunidades e turmas, agora organizados por categorias
        const communitiesData = {
            "Matriz": {
                "Pré Catequese": [],
                "Primeira Eucaristia": [
                    {
                        name: "Catequese Sábado",
                        year: "2026",
                        catechists: "Edu, Paloma, Penha",
                        formUrl: "https://docs.google.com/forms/d/e/1FAIpQLSfoUN-RaIiyTIFKzDps6WMBB7bIMe505W4MSKgvgW5KuETDRA/viewform?embedded=true"
                    }
                ],
                "Crisma": [
                    {
                        name: "Crisma Domingo",
                        year: "2026",
                        catechists: "Wellington, Felipe",
                        formUrl: "https://docs.google.com/forms/d/e/1FAIpQLSfAOuVYWhvmmSTCv8v9knuXD6IOlFxJ9jVzd5wqga7lkhTgTA/viewform?embedded=true"
                    }
                ]
            },
            "Santa Filomena": {
                "Pré Catequese": [],
                "Primeira Eucaristia": [
                    {
                        name: "Primeira Eucaristia - Sábado",
                        year: "2027",
                        catechists: "Kary, Virginia",
                        formUrl: "https://docs.google.com/forms/d/e/1FAIpQLSfAOuVYWhvmmSTCv8v9knxXD6IOlFxJ9jVzd5wqga7lkhTgTA/viewform?embedded=true" // Placeholder
                    }
                ],
                "Crisma": [
                    {
                        name: "Crisma - Domingo",
                        year: "2027",
                        catechists: "Éder",
                        formUrl: "https://docs.google.com/forms/d/e/1FAIpQLSfoUN-RaIiyTIFKzDps6WMBB7bIMe505W4MSKgvgW5KuETDRA/viewform?embedded=true" // Placeholder
                    }
                ]
            },
            "Nossa Senhora de Fátima": {
                "Pré Catequese": [],
                "Primeira Eucaristia": [
                    {
                        name: "Primeira Eucaristia - Sábado", // Assumindo que "Catequese Infantil" se encaixa aqui
                        year: "2027",
                        catechists: "Michelle, Andreia",
                        formUrl: "https://docs.google.com/forms/d/e/1FAIpQLSfAOuVYWhvmmSTCv8v9knxXD6IOlFxJ9jVzd5wqga7lkhTgTA/viewform?embedded=true" // Placeholder
                    }
                ],
                "Crisma": []
            }
        };

        // Função para mostrar uma página e esconder as outras
        function showPage(pageId) {
            const pages = document.querySelectorAll('.page');
            pages.forEach(page => {
                if (page.id === pageId) {
                    page.classList.remove('hidden-page');
                } else {
                    page.classList.add('hidden-page');
                }
            });
            // Esconde o iframe do Google Forms ao mudar de página, a menos que seja a página de turmas e já esteja visível
            if (pageId !== 'turmas-page' || document.getElementById('google-forms-embed').classList.contains('hidden-page')) {
                hideFormsIframe();
            }
        }

        // Função para esconder o iframe do Google Forms
        function hideFormsIframe() {
            const formsEmbed = document.getElementById('google-forms-embed');
            const formsIframe = document.getElementById('forms-iframe');
            formsEmbed.classList.add('hidden-page');
            formsIframe.src = ""; // Limpa o src para garantir que o formulário não seja carregado em segundo plano
        }

        // Função para exibir as turmas de uma comunidade específica, divididas por categoria
        function showTurmas(communityName) {
            showPage('turmas-page'); // Mostra a página de turmas
            document.getElementById('turmas-title').textContent = `Turmas da Comunidade ${communityName}`;
            const turmasList = document.getElementById('turmas-list');
            turmasList.innerHTML = ''; // Limpa a lista de turmas anterior
            hideFormsIframe(); // Esconde o iframe ao carregar a lista de turmas

            const categoriesOrder = ["Pré Catequese", "Primeira Eucaristia", "Crisma"];
            const communityCategories = communitiesData[communityName];
            let totalTurmasCount = 0;

            categoriesOrder.forEach(categoryName => {
                const turmas = communityCategories[categoryName];

                if (turmas && turmas.length > 0) {
                    totalTurmasCount += turmas.length;

                    // Cria o título da categoria e o divisor
                    const categoryHeading = document.createElement('h3');
                    categoryHeading.className = "text-[#333333] text-2xl font-semibold mt-8 mb-4 border-b-2 border-gray-300 pb-2";
                    categoryHeading.textContent = categoryName;
                    turmasList.appendChild(categoryHeading);

                    // Cria um contêiner para os cards dentro desta categoria para o layout em grid
                    const categoryCardsContainer = document.createElement('div');
                    categoryCardsContainer.className = "grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6";
                    turmasList.appendChild(categoryCardsContainer);

                    turmas.forEach(turma => {
                        const turmaCard = document.createElement('div');
                        turmaCard.className = `
                            bg-white p-6 rounded-lg shadow-md hover:shadow-lg transition-shadow duration-300
                            cursor-pointer transform hover:-translate-y-1 hover:scale-102
                            border border-gray-200
                        `;
                        turmaCard.innerHTML = `
                            <h3 class="text-xl font-semibold text-[#CC0000] mb-2">${turma.name}</h3>
                            <p class="text-gray-700 text-sm mb-1"><span class="font-medium">Conclusão:</span> ${turma.year}</p>
                            <p class="text-gray-700 text-sm"><span class="font-medium">Catequista(s):</span> ${turma.catechists}</p>
                        `;
                        // Adiciona o evento de clique para abrir o formulário
                        turmaCard.onclick = () => openFormsIframe(turma.formUrl);
                        categoryCardsContainer.appendChild(turmaCard);
                    });
                }
            });

            // Mensagem se nenhuma turma for encontrada em todas as categorias
            if (totalTurmasCount === 0) {
                turmasList.innerHTML = `<p class="text-center text-gray-600 col-span-full">Nenhuma turma cadastrada para esta comunidade.</p>`;
            }
        }

        // Função para abrir o iframe do Google Forms
        function openFormsIframe(formUrl) {
            const formsEmbed = document.getElementById('google-forms-embed');
            const formsIframe = document.getElementById('forms-iframe');
            formsIframe.src = formUrl;
            formsEmbed.classList.remove('hidden-page'); // Mostra o contêiner do iframe
            // Rola para o iframe para que ele fique visível, especialmente em telas pequenas
            formsIframe.scrollIntoView({ behavior: 'smooth', block: 'start' });
        }

        // Inicializa a página de boas-vindas ao carregar
        document.addEventListener('DOMContentLoaded', () => {
            showPage('welcome-page');
        });
    </script>
</body>
</html>
