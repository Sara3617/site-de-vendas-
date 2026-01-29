# site-de-vendas-
[index (1).html](https://github.com/user-attachments/files/24947507/index.1.html)
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TechStore - Eletrônicos de Última Geração</title>
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.4.0/css/all.min.css">
    
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800;900&display=swap" rel="stylesheet">
    
    <!-- Custom CSS -->
    <link rel="stylesheet" href="css/style.css">
    
    <style>
        * {
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
        }
    </style>
</head>
<body class="bg-black text-white overflow-x-hidden">
    
    <!-- Header -->
    <header class="fixed top-0 left-0 right-0 z-50 glass-effect">
        <nav class="container mx-auto px-6 py-4">
            <div class="flex items-center justify-between">
                <!-- Logo -->
                <div class="flex items-center space-x-2">
                    <div class="logo-container">
                        <i class="fas fa-bolt text-3xl neon-text"></i>
                    </div>
                    <span class="text-2xl font-bold tracking-tight">Tech<span class="neon-text">Store</span></span>
                </div>
                
                <!-- Navigation Menu -->
                <div class="hidden md:flex items-center space-x-8">
                    <a href="#home" class="nav-link">Início</a>
                    <a href="#products" class="nav-link">Produtos</a>
                    <a href="#deals" class="nav-link">Promoções</a>
                    <a href="#about" class="nav-link">Sobre</a>
                    <a href="#contact" class="nav-link">Contato</a>
                </div>
                
                <!-- Cart & Menu -->
                <div class="flex items-center space-x-6">
                    <button class="cart-button relative">
                        <i class="fas fa-shopping-cart text-xl"></i>
                        <span class="cart-badge">0</span>
                    </button>
                    <button class="md:hidden text-2xl" id="menuToggle">
                        <i class="fas fa-bars"></i>
                    </button>
                </div>
            </div>
            
            <!-- Mobile Menu -->
            <div class="mobile-menu hidden mt-6 md:hidden" id="mobileMenu">
                <a href="#home" class="block py-2 nav-link">Início</a>
                <a href="#products" class="block py-2 nav-link">Produtos</a>
                <a href="#deals" class="block py-2 nav-link">Promoções</a>
                <a href="#about" class="block py-2 nav-link">Sobre</a>
                <a href="#contact" class="block py-2 nav-link">Contato</a>
            </div>
        </nav>
    </header>
    
    <!-- Hero Banner -->
    <section id="home" class="hero-section pt-32 pb-20">
        <div class="container mx-auto px-6">
            <div class="grid md:grid-cols-2 gap-12 items-center">
                <div class="space-y-6 animate-fade-in">
                    <div class="inline-block">
                        <span class="badge-new">Novidades 2026</span>
                    </div>
                    <h1 class="text-5xl md:text-7xl font-black leading-tight">
                        O Futuro da
                        <span class="neon-text glow-text">Tecnologia</span>
                        Está Aqui
                    </h1>
                    <p class="text-gray-400 text-lg md:text-xl">
                        Explore nossa coleção exclusiva de eletrônicos premium. Inovação, design e performance em cada produto.
                    </p>
                    <div class="flex flex-wrap gap-4">
                        <button class="btn-primary">
                            Explorar Produtos
                            <i class="fas fa-arrow-right ml-2"></i>
                        </button>
                        <button class="btn-secondary">
                            Ver Ofertas
                            <i class="fas fa-tags ml-2"></i>
                        </button>
                    </div>
                    
                    <!-- Stats -->
                    <div class="grid grid-cols-3 gap-6 pt-8">
                        <div class="stat-card">
                            <div class="text-3xl font-bold neon-text">500+</div>
                            <div class="text-gray-500 text-sm">Produtos</div>
                        </div>
                        <div class="stat-card">
                            <div class="text-3xl font-bold neon-text">50k+</div>
                            <div class="text-gray-500 text-sm">Clientes</div>
                        </div>
                        <div class="stat-card">
                            <div class="text-3xl font-bold neon-text">4.9★</div>
                            <div class="text-gray-500 text-sm">Avaliação</div>
                        </div>
                    </div>
                </div>
                
                <!-- Hero Image -->
                <div class="relative animate-float">
                    <div class="hero-image-container">
                        <div class="glow-circle"></div>
                        <div class="hero-products">
                            <i class="fas fa-mobile-alt product-icon" style="top: 10%; left: 20%;"></i>
                            <i class="fas fa-laptop product-icon" style="top: 40%; right: 15%;"></i>
                            <i class="fas fa-headphones product-icon" style="bottom: 20%; left: 25%;"></i>
                            <i class="fas fa-tablet-alt product-icon" style="top: 25%; right: 30%;"></i>
                            <i class="fas fa-smartwatch product-icon" style="bottom: 30%; right: 20%;"></i>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Categories -->
    <section class="py-16 bg-gradient-to-b from-black to-gray-900">
        <div class="container mx-auto px-6">
            <div class="grid grid-cols-2 md:grid-cols-4 gap-6">
                <div class="category-card">
                    <i class="fas fa-mobile-alt text-4xl mb-4 neon-text"></i>
                    <h3 class="text-lg font-semibold">Smartphones</h3>
                </div>
                <div class="category-card">
                    <i class="fas fa-laptop text-4xl mb-4 neon-text"></i>
                    <h3 class="text-lg font-semibold">Notebooks</h3>
                </div>
                <div class="category-card">
                    <i class="fas fa-headphones text-4xl mb-4 neon-text"></i>
                    <h3 class="text-lg font-semibold">Áudio</h3>
                </div>
                <div class="category-card">
                    <i class="fas fa-gamepad text-4xl mb-4 neon-text"></i>
                    <h3 class="text-lg font-semibold">Gaming</h3>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Products Section -->
    <section id="products" class="py-20 bg-gray-900">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <span class="text-sm font-semibold tracking-widest text-blue-400 uppercase">Produtos Premium</span>
                <h2 class="text-4xl md:text-5xl font-black mt-2 mb-4">
                    Em <span class="neon-text">Destaque</span>
                </h2>
                <p class="text-gray-400 text-lg max-w-2xl mx-auto">
                    Descubra os eletrônicos mais avançados do mercado
                </p>
            </div>
            
            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
                <!-- Product 1 -->
                <div class="product-card">
                    <div class="product-image">
                        <span class="product-badge">Novo</span>
                        <i class="fas fa-mobile-alt text-8xl neon-text"></i>
                    </div>
                    <div class="product-info">
                        <h3 class="product-title">Galaxy X Pro</h3>
                        <p class="product-description">Smartphone flagship com câmera 200MP</p>
                        <div class="product-rating">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <span class="ml-2 text-gray-400">(1.2k)</span>
                        </div>
                        <div class="flex items-center justify-between mt-4">
                            <div class="product-price">R$ 5.999</div>
                            <button class="btn-buy">
                                <i class="fas fa-shopping-cart"></i>
                                Comprar
                            </button>
                        </div>
                    </div>
                </div>
                
                <!-- Product 2 -->
                <div class="product-card">
                    <div class="product-image">
                        <span class="product-badge hot">Hot</span>
                        <i class="fas fa-laptop text-8xl neon-text"></i>
                    </div>
                    <div class="product-info">
                        <h3 class="product-title">UltraBook Pro M2</h3>
                        <p class="product-description">16GB RAM, 512GB SSD, Tela 4K</p>
                        <div class="product-rating">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star-half-alt"></i>
                            <span class="ml-2 text-gray-400">(890)</span>
                        </div>
                        <div class="flex items-center justify-between mt-4">
                            <div class="product-price">R$ 8.499</div>
                            <button class="btn-buy">
                                <i class="fas fa-shopping-cart"></i>
                                Comprar
                            </button>
                        </div>
                    </div>
                </div>
                
                <!-- Product 3 -->
                <div class="product-card">
                    <div class="product-image">
                        <i class="fas fa-headphones text-8xl neon-text"></i>
                    </div>
                    <div class="product-info">
                        <h3 class="product-title">AirPods Max Ultra</h3>
                        <p class="product-description">Cancelamento de ruído premium</p>
                        <div class="product-rating">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <span class="ml-2 text-gray-400">(2.5k)</span>
                        </div>
                        <div class="flex items-center justify-between mt-4">
                            <div class="product-price">R$ 2.799</div>
                            <button class="btn-buy">
                                <i class="fas fa-shopping-cart"></i>
                                Comprar
                            </button>
                        </div>
                    </div>
                </div>
                
                <!-- Product 4 -->
                <div class="product-card">
                    <div class="product-image">
                        <span class="product-badge">Oferta</span>
                        <i class="fas fa-tablet-alt text-8xl neon-text"></i>
                    </div>
                    <div class="product-info">
                        <h3 class="product-title">Tablet Pro 12.9"</h3>
                        <p class="product-description">M2 Chip, 256GB, 5G</p>
                        <div class="product-rating">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star-half-alt"></i>
                            <span class="ml-2 text-gray-400">(650)</span>
                        </div>
                        <div class="flex items-center justify-between mt-4">
                            <div class="product-price">R$ 6.499</div>
                            <button class="btn-buy">
                                <i class="fas fa-shopping-cart"></i>
                                Comprar
                            </button>
                        </div>
                    </div>
                </div>
                
                <!-- Product 5 -->
                <div class="product-card">
                    <div class="product-image">
                        <i class="fas fa-smartwatch text-8xl neon-text"></i>
                    </div>
                    <div class="product-info">
                        <h3 class="product-title">SmartWatch Series 9</h3>
                        <p class="product-description">Fitness, saúde e GPS integrado</p>
                        <div class="product-rating">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <span class="ml-2 text-gray-400">(1.8k)</span>
                        </div>
                        <div class="flex items-center justify-between mt-4">
                            <div class="product-price">R$ 3.299</div>
                            <button class="btn-buy">
                                <i class="fas fa-shopping-cart"></i>
                                Comprar
                            </button>
                        </div>
                    </div>
                </div>
                
                <!-- Product 6 -->
                <div class="product-card">
                    <div class="product-image">
                        <span class="product-badge hot">Top</span>
                        <i class="fas fa-camera text-8xl neon-text"></i>
                    </div>
                    <div class="product-info">
                        <h3 class="product-title">Camera Mirrorless 4K</h3>
                        <p class="product-description">50MP, Gravação 8K, Wi-Fi</p>
                        <div class="product-rating">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star-half-alt"></i>
                            <span class="ml-2 text-gray-400">(420)</span>
                        </div>
                        <div class="flex items-center justify-between mt-4">
                            <div class="product-price">R$ 12.999</div>
                            <button class="btn-buy">
                                <i class="fas fa-shopping-cart"></i>
                                Comprar
                            </button>
                        </div>
                    </div>
                </div>
                
                <!-- Product 7 -->
                <div class="product-card">
                    <div class="product-image">
                        <i class="fas fa-gamepad text-8xl neon-text"></i>
                    </div>
                    <div class="product-info">
                        <h3 class="product-title">Console NextGen Pro</h3>
                        <p class="product-description">8K Gaming, 2TB SSD, Ray Tracing</p>
                        <div class="product-rating">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <span class="ml-2 text-gray-400">(3.1k)</span>
                        </div>
                        <div class="flex items-center justify-between mt-4">
                            <div class="product-price">R$ 4.999</div>
                            <button class="btn-buy">
                                <i class="fas fa-shopping-cart"></i>
                                Comprar
                            </button>
                        </div>
                    </div>
                </div>
                
                <!-- Product 8 -->
                <div class="product-card">
                    <div class="product-image">
                        <span class="product-badge">Novo</span>
                        <i class="fas fa-tv text-8xl neon-text"></i>
                    </div>
                    <div class="product-info">
                        <h3 class="product-title">Smart TV OLED 65"</h3>
                        <p class="product-description">4K HDR, 120Hz, Dolby Vision</p>
                        <div class="product-rating">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <span class="ml-2 text-gray-400">(980)</span>
                        </div>
                        <div class="flex items-center justify-between mt-4">
                            <div class="product-price">R$ 9.999</div>
                            <button class="btn-buy">
                                <i class="fas fa-shopping-cart"></i>
                                Comprar
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Deals Section -->
    <section id="deals" class="py-20 bg-black relative overflow-hidden">
        <div class="absolute inset-0 opacity-10">
            <div class="absolute top-0 left-1/4 w-96 h-96 bg-blue-500 rounded-full blur-3xl"></div>
            <div class="absolute bottom-0 right-1/4 w-96 h-96 bg-purple-500 rounded-full blur-3xl"></div>
        </div>
        
        <div class="container mx-auto px-6 relative z-10">
            <div class="text-center mb-16">
                <span class="text-sm font-semibold tracking-widest text-blue-400 uppercase">Ofertas Especiais</span>
                <h2 class="text-4xl md:text-5xl font-black mt-2 mb-4">
                    <span class="neon-text">Super Promoções</span>
                </h2>
                <p class="text-gray-400 text-lg max-w-2xl mx-auto">
                    Aproveite descontos incríveis por tempo limitado
                </p>
            </div>
            
            <div class="grid md:grid-cols-3 gap-8">
                <!-- Deal 1 -->
                <div class="deal-card">
                    <div class="deal-badge">
                        <div class="text-3xl font-black">40%</div>
                        <div class="text-sm">OFF</div>
                    </div>
                    <i class="fas fa-keyboard text-6xl neon-text mb-4"></i>
                    <h3 class="text-2xl font-bold mb-2">Teclado Mecânico RGB</h3>
                    <p class="text-gray-400 mb-4">Switch customizado, iluminação avançada</p>
                    <div class="flex items-center justify-between">
                        <div>
                            <div class="text-sm line-through text-gray-500">R$ 899</div>
                            <div class="text-2xl font-bold neon-text">R$ 539</div>
                        </div>
                        <button class="btn-deal">
                            Aproveitar
                        </button>
                    </div>
                </div>
                
                <!-- Deal 2 -->
                <div class="deal-card">
                    <div class="deal-badge">
                        <div class="text-3xl font-black">35%</div>
                        <div class="text-sm">OFF</div>
                    </div>
                    <i class="fas fa-mouse text-6xl neon-text mb-4"></i>
                    <h3 class="text-2xl font-bold mb-2">Mouse Gamer Pro</h3>
                    <p class="text-gray-400 mb-4">20.000 DPI, sensor óptico de precisão</p>
                    <div class="flex items-center justify-between">
                        <div>
                            <div class="text-sm line-through text-gray-500">R$ 459</div>
                            <div class="text-2xl font-bold neon-text">R$ 298</div>
                        </div>
                        <button class="btn-deal">
                            Aproveitar
                        </button>
                    </div>
                </div>
                
                <!-- Deal 3 -->
                <div class="deal-card">
                    <div class="deal-badge">
                        <div class="text-3xl font-black">50%</div>
                        <div class="text-sm">OFF</div>
                    </div>
                    <i class="fas fa-microphone text-6xl neon-text mb-4"></i>
                    <h3 class="text-2xl font-bold mb-2">Microfone Condensador</h3>
                    <p class="text-gray-400 mb-4">USB, cancelamento de ruído, streaming</p>
                    <div class="flex items-center justify-between">
                        <div>
                            <div class="text-sm line-through text-gray-500">R$ 799</div>
                            <div class="text-2xl font-bold neon-text">R$ 399</div>
                        </div>
                        <button class="btn-deal">
                            Aproveitar
                        </button>
                    </div>
                </div>
            </div>
            
            <!-- Countdown Timer -->
            <div class="mt-16 text-center">
                <div class="inline-block glass-card p-8 rounded-2xl">
                    <p class="text-sm text-gray-400 mb-4">Promoção termina em:</p>
                    <div class="flex gap-6 justify-center">
                        <div class="timer-box">
                            <div class="text-4xl font-black neon-text" id="hours">23</div>
                            <div class="text-xs text-gray-500 mt-1">HORAS</div>
                        </div>
                        <div class="text-3xl text-gray-600">:</div>
                        <div class="timer-box">
                            <div class="text-4xl font-black neon-text" id="minutes">45</div>
                            <div class="text-xs text-gray-500 mt-1">MIN</div>
                        </div>
                        <div class="text-3xl text-gray-600">:</div>
                        <div class="timer-box">
                            <div class="text-4xl font-black neon-text" id="seconds">12</div>
                            <div class="text-xs text-gray-500 mt-1">SEG</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Features Section -->
    <section class="py-20 bg-gray-900">
        <div class="container mx-auto px-6">
            <div class="grid md:grid-cols-4 gap-8">
                <div class="feature-card">
                    <i class="fas fa-shipping-fast text-4xl neon-text mb-4"></i>
                    <h3 class="text-lg font-semibold mb-2">Entrega Rápida</h3>
                    <p class="text-gray-400 text-sm">Frete grátis acima de R$ 299</p>
                </div>
                <div class="feature-card">
                    <i class="fas fa-shield-alt text-4xl neon-text mb-4"></i>
                    <h3 class="text-lg font-semibold mb-2">Compra Segura</h3>
                    <p class="text-gray-400 text-sm">Proteção total em pagamentos</p>
                </div>
                <div class="feature-card">
                    <i class="fas fa-sync-alt text-4xl neon-text mb-4"></i>
                    <h3 class="text-lg font-semibold mb-2">Troca Garantida</h3>
                    <p class="text-gray-400 text-sm">30 dias para trocas e devoluções</p>
                </div>
                <div class="feature-card">
                    <i class="fas fa-headset text-4xl neon-text mb-4"></i>
                    <h3 class="text-lg font-semibold mb-2">Suporte 24/7</h3>
                    <p class="text-gray-400 text-sm">Atendimento sempre disponível</p>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Newsletter -->
    <section class="py-20 bg-black">
        <div class="container mx-auto px-6">
            <div class="glass-card rounded-3xl p-12 text-center max-w-3xl mx-auto">
                <i class="fas fa-envelope text-5xl neon-text mb-6"></i>
                <h2 class="text-3xl md:text-4xl font-black mb-4">
                    Fique por Dentro das <span class="neon-text">Novidades</span>
                </h2>
                <p class="text-gray-400 mb-8">
                    Receba ofertas exclusivas, lançamentos e promoções especiais direto no seu email
                </p>
                <form class="flex flex-col md:flex-row gap-4 max-w-xl mx-auto">
                    <input type="email" placeholder="Seu melhor email" class="newsletter-input flex-1">
                    <button type="submit" class="btn-primary">
                        Inscrever-se
                        <i class="fas fa-paper-plane ml-2"></i>
                    </button>
                </form>
            </div>
        </div>
    </section>
    
    <!-- Footer -->
    <footer class="bg-gray-950 pt-16 pb-8">
        <div class="container mx-auto px-6">
            <div class="grid md:grid-cols-4 gap-12 mb-12">
                <!-- Company Info -->
                <div>
                    <div class="flex items-center space-x-2 mb-4">
                        <i class="fas fa-bolt text-2xl neon-text"></i>
                        <span class="text-xl font-bold">Tech<span class="neon-text">Store</span></span>
                    </div>
                    <p class="text-gray-400 text-sm mb-6">
                        A melhor loja de eletrônicos premium do Brasil. Inovação e qualidade garantidas.
                    </p>
                    <div class="flex space-x-4">
                        <a href="#" class="social-icon">
                            <i class="fab fa-facebook-f"></i>
                        </a>
                        <a href="#" class="social-icon">
                            <i class="fab fa-instagram"></i>
                        </a>
                        <a href="#" class="social-icon">
                            <i class="fab fa-twitter"></i>
                        </a>
                        <a href="#" class="social-icon">
                            <i class="fab fa-youtube"></i>
                        </a>
                    </div>
                </div>
                
                <!-- Links -->
                <div>
                    <h4 class="font-semibold mb-4">Empresa</h4>
                    <ul class="space-y-2 text-gray-400 text-sm">
                        <li><a href="#" class="hover:text-blue-400 transition">Sobre Nós</a></li>
                        <li><a href="#" class="hover:text-blue-400 transition">Carreiras</a></li>
                        <li><a href="#" class="hover:text-blue-400 transition">Blog</a></li>
                        <li><a href="#" class="hover:text-blue-400 transition">Imprensa</a></li>
                    </ul>
                </div>
                
                <!-- Support -->
                <div>
                    <h4 class="font-semibold mb-4">Suporte</h4>
                    <ul class="space-y-2 text-gray-400 text-sm">
                        <li><a href="#" class="hover:text-blue-400 transition">Central de Ajuda</a></li>
                        <li><a href="#" class="hover:text-blue-400 transition">Rastreamento</a></li>
                        <li><a href="#" class="hover:text-blue-400 transition">Trocas e Devoluções</a></li>
                        <li><a href="#" class="hover:text-blue-400 transition">Garantia</a></li>
                    </ul>
                </div>
                
                <!-- Contact -->
                <div>
                    <h4 class="font-semibold mb-4">Contato</h4>
                    <ul class="space-y-3 text-gray-400 text-sm">
                        <li class="flex items-start space-x-2">
                            <i class="fas fa-phone mt-1 neon-text"></i>
                            <span>(11) 3000-0000</span>
                        </li>
                        <li class="flex items-start space-x-2">
                            <i class="fas fa-envelope mt-1 neon-text"></i>
                            <span>contato@techstore.com.br</span>
                        </li>
                        <li class="flex items-start space-x-2">
                            <i class="fas fa-map-marker-alt mt-1 neon-text"></i>
                            <span>Av. Paulista, 1000<br>São Paulo - SP</span>
                        </li>
                    </ul>
                </div>
            </div>
            
            <!-- Payment Methods -->
            <div class="border-t border-gray-800 pt-8 mb-8">
                <h4 class="font-semibold mb-4 text-center">Formas de Pagamento</h4>
                <div class="flex flex-wrap justify-center gap-4 text-3xl text-gray-600">
                    <i class="fab fa-cc-visa hover:text-blue-400 transition"></i>
                    <i class="fab fa-cc-mastercard hover:text-blue-400 transition"></i>
                    <i class="fab fa-cc-amex hover:text-blue-400 transition"></i>
                    <i class="fab fa-cc-paypal hover:text-blue-400 transition"></i>
                    <i class="fas fa-credit-card hover:text-blue-400 transition"></i>
                    <i class="fas fa-barcode hover:text-blue-400 transition"></i>
                    <i class="fab fa-pix hover:text-blue-400 transition"></i>
                </div>
            </div>
            
            <!-- Copyright -->
            <div class="border-t border-gray-800 pt-8 text-center text-gray-500 text-sm">
                <p>&copy; 2026 TechStore. Todos os direitos reservados.</p>
                <div class="mt-2 space-x-4">
                    <a href="#" class="hover:text-blue-400 transition">Termos de Uso</a>
                    <span>|</span>
                    <a href="#" class="hover:text-blue-400 transition">Política de Privacidade</a>
                    <span>|</span>
                    <a href="#" class="hover:text-blue-400 transition">Cookies</a>
                </div>
            </div>
        </div>
    </footer>
    
    <!-- Scroll to Top Button -->
    <button id="scrollTop" class="scroll-top-btn">
        <i class="fas fa-arrow-up"></i>
    </button>
    
    <!-- Custom JavaScript -->
    <script src="js/main.js"></script>
</body>
</html>
