<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PASHMINA INNER PREMIUM - Tampil Anggun dengan Kenyamanan Maksimal</title>
    <meta name="description" content="Pashmina Inner Premium - Bahan lembut, adem, dan tidak menerawang. Cocok untuk sehari-hari maupun acara spesial. Diskon 40% hari ini!">
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: '#667eea',
                        secondary: '#764ba2',
                    },
                    backgroundImage: {
                        'gradient-blue': 'linear-gradient(to right, #667eea, #764ba2)',
                    },
                    animation: {
                        'pulse-slow': 'pulse 3s cubic-bezier(0.4, 0, 0.6, 1) infinite',
                        'float': 'float 6s ease-in-out infinite',
                    },
                    keyframes: {
                        float: {
                            '0%, 100%': { transform: 'translateY(0)' },
                            '50%': { transform: 'translateY(-20px)' },
                        }
                    }
                }
            }
        }
    </script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500;600;700&family=Poppins:wght@300;400;500;600;700&display=swap');
        
        body {
            font-family: 'Poppins', sans-serif;
            scroll-behavior: smooth;
        }
        
        .font-playfair {
            font-family: 'Playfair Display', serif;
        }
        
        .hero-section {
            background: linear-gradient(135deg, rgba(102, 126, 234, 0.9) 0%, rgba(118, 75, 162, 0.9) 100%), url('https://images.unsplash.com/photo-1525507119028-ed4c629a60a3?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80');
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
        }
        
        .product-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
        }
        
        .testimonial-card {
            transition: all 0.3s ease;
        }
        
        .testimonial-card:hover {
            transform: scale(1.03);
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
        }
        
        .floating-whatsapp {
            animation: float 6s ease-in-out infinite;
        }
        
        .countdown-box {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
        }
        
        .zoom-effect {
            transition: transform 0.3s ease;
        }
        
        .zoom-effect:hover {
            transform: scale(1.05);
        }
        
        /* Custom scrollbar */
        ::-webkit-scrollbar {
            width: 8px;
        }
        
        ::-webkit-scrollbar-track {
            background: #f1f1f1;
        }
        
        ::-webkit-scrollbar-thumb {
            background: linear-gradient(to bottom, #667eea, #764ba2);
            border-radius: 10px;
        }
        
        /* Modal styles */
        .modal {
            transition: all 0.3s ease;
            opacity: 0;
            visibility: hidden;
        }
        
        .modal.active {
            opacity: 1;
            visibility: visible;
        }
        
        /* Gallery zoom */
        .gallery-item {
            transition: all 0.3s ease;
        }
        
        .gallery-item:hover {
            transform: scale(1.03);
        }
        
        /* FAQ accordion */
        .faq-item {
            transition: all 0.3s ease;
        }
        
        .faq-answer {
            max-height: 0;
            overflow: hidden;
            transition: max-height 0.3s ease;
        }
        
        .faq-item.active .faq-answer {
            max-height: 500px;
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">
    <!-- WhatsApp Floating Button -->
    <a href="https://wa.me/6281252255248?text=Saya%20tertarik%20dengan%20Pashmina%20Inner%20Premium" 
       class="fixed bottom-8 right-8 bg-green-500 text-white w-16 h-16 rounded-full flex items-center justify-center text-3xl shadow-lg z-50 floating-whatsapp hover:bg-green-600 transition-colors">
        <i class="fab fa-whatsapp"></i>
    </a>

    <!-- Navigation -->
    <nav class="bg-white shadow-md sticky top-0 z-40">
        <div class="container mx-auto px-4 py-3 flex justify-between items-center">
            <a href="#" class="text-2xl font-bold text-primary font-playfair">PASHMINA INNER PREMIUM</a>
            <div class="hidden md:flex space-x-8">
                <a href="#features" class="hover:text-primary transition-colors">Fitur</a>
                <a href="#gallery" class="hover:text-primary transition-colors">Galeri</a>
                <a href="#testimonials" class="hover:text-primary transition-colors">Testimoni</a>
                <a href="#faq" class="hover:text-primary transition-colors">FAQ</a>
            </div>
            <a href="https://nava.orderonline.id/pashmina-premium1" 
               class="bg-gradient-to-r from-primary to-secondary text-white px-6 py-2 rounded-full font-medium hover:opacity-90 transition-opacity shadow-md">
                ORDER SEKARANG
            </a>
            <button class="md:hidden text-gray-700" id="mobile-menu-button">
                <i class="fas fa-bars text-2xl"></i>
            </button>
        </div>
        
        <!-- Mobile Menu -->
        <div class="md:hidden hidden bg-white w-full py-4 px-4 shadow-md" id="mobile-menu">
            <a href="#features" class="block py-2 hover:text-primary transition-colors">Fitur</a>
            <a href="#gallery" class="block py-2 hover:text-primary transition-colors">Galeri</a>
            <a href="#testimonials" class="block py-2 hover:text-primary transition-colors">Testimoni</a>
            <a href="#faq" class="block py-2 hover:text-primary transition-colors">FAQ</a>
            <a href="https://nava.orderonline.id/pashmina-premium1" 
               class="block bg-gradient-to-r from-primary to-secondary text-white px-6 py-2 rounded-full font-medium hover:opacity-90 transition-opacity shadow-md text-center mt-2">
                ORDER SEKARANG
            </a>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero-section text-white py-20 md:py-32">
        <div class="container mx-auto px-4 flex flex-col md:flex-row items-center">
            <div class="md:w-1/2 mb-10 md:mb-0">
                <h1 class="text-4xl md:text-5xl lg:text-6xl font-bold mb-6 font-playfair">Tampil Anggun dengan <span class="text-yellow-300">Pashmina Inner Premium</span></h1>
                <p class="text-xl mb-8">Bahan premium lembut, adem, dan tidak menerawang. Cocok untuk sehari-hari maupun acara spesial.</p>
                
                <div class="bg-white bg-opacity-20 backdrop-filter backdrop-blur-sm rounded-lg p-4 mb-8 inline-block">
                    <div class="flex items-center">
                        <div class="text-3xl font-bold text-yellow-300 mr-4">
                            <span id="countdown-hours">12</span>:
                            <span id="countdown-minutes">00</span>:
                            <span id="countdown-seconds">00</span>
                        </div>
                        <div>
                            <div class="text-sm">PROMO TERBATAS</div>
                            <div class="font-bold">DISKON 40% HARI INI!</div>
                        </div>
                    </div>
                </div>
                
                <div class="flex flex-col sm:flex-row space-y-4 sm:space-y-0 sm:space-x-4">
                    <a href="https://nava.orderonline.id/pashmina-premium1" 
                       class="bg-yellow-400 hover:bg-yellow-500 text-gray-900 font-bold py-4 px-8 rounded-full text-center transition-colors shadow-lg">
                        <span class="text-lg">BELI SEKARANG</span><br>
                        <span class="text-sm">Dapatkan Diskon 40%</span>
                    </a>
                    <a href="#features" 
                       class="bg-white bg-opacity-20 hover:bg-opacity-30 text-white font-bold py-4 px-8 rounded-full text-center transition-colors shadow-lg">
                        <span class="text-lg">LIHAT DETAIL</span><br>
                        <span class="text-sm">Keunggulan Produk</span>
                    </a>
                </div>
                
                <div class="mt-8 flex items-center">
                    <div class="flex mr-4">
                        <i class="fas fa-star text-yellow-400"></i>
                        <i class="fas fa-star text-yellow-400"></i>
                        <i class="fas fa-star text-yellow-400"></i>
                        <i class="fas fa-star text-yellow-400"></i>
                        <i class="fas fa-star text-yellow-400"></i>
                    </div>
                    <div>5000+ Pelanggan Puas</div>
                </div>
            </div>
            <div class="md:w-1/2 flex justify-center">
                <div class="relative">
                    <img src="https://cdn.orderonline.id/uploads/images_6473271741261731048.png" 
                         alt="Pashmina Inner Premium" 
                         class="rounded-lg shadow-2xl w-full max-w-md transform transition-transform duration-500 hover:scale-105">
                    <div class="absolute -bottom-5 -right-5 bg-white text-primary p-4 rounded-full shadow-xl">
                        <div class="text-center">
                            <div class="line-through text-gray-500 text-sm">Rp241,000</div>
                            <div class="font-bold text-2xl">Rp145,000</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Trust Badges -->
    <section class="bg-gray-100 py-8">
        <div class="container mx-auto px-4">
            <div class="flex flex-wrap justify-center items-center gap-8 md:gap-16">
                <div class="flex items-center">
                    <i class="fas fa-check-circle text-green-500 text-3xl mr-3"></i>
                    <span>100% Original</span>
                </div>
                <div class="flex items-center">
                    <i class="fas fa-truck text-primary text-3xl mr-3"></i>
                    <span>Gratis Ongkir</span>
                </div>
                <div class="flex items-center">
                    <i class="fas fa-shield-alt text-secondary text-3xl mr-3"></i>
                    <span>Garansi Kepuasan</span>
                </div>
                <div class="flex items-center">
                    <i class="fas fa-credit-card text-yellow-500 text-3xl mr-3"></i>
                    <span>COD Available</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section id="features" class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold mb-4 font-playfair">Kenapa Memilih <span class="text-primary">Pashmina Inner Premium</span>?</h2>
                <p class="text-lg text-gray-600 max-w-3xl mx-auto">Didesain khusus untuk memberikan kenyamanan maksimal dengan gaya yang elegan dan premium.</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="bg-gray-50 rounded-xl p-8 shadow-md hover:shadow-xl transition-shadow">
                    <div class="bg-primary bg-opacity-10 text-primary w-16 h-16 rounded-full flex items-center justify-center mb-6 mx-auto">
                        <i class="fas fa-tshirt text-3xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3 text-center">Bahan Premium</h3>
                    <p class="text-gray-600 text-center">Terbuat dari bahan berkualitas tinggi yang lembut, adem, dan tidak menerawang. Nyaman digunakan seharian.</p>
                </div>
                
                <div class="bg-gray-50 rounded-xl p-8 shadow-md hover:shadow-xl transition-shadow">
                    <div class="bg-primary bg-opacity-10 text-primary w-16 h-16 rounded-full flex items-center justify-center mb-6 mx-auto">
                        <i class="fas fa-wind text-3xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3 text-center">Sirkulasi Udara Baik</h3>
                    <p class="text-gray-600 text-center">Desain yang memungkinkan sirkulasi udara optimal sehingga tidak gerah meski dipakai lama.</p>
                </div>
                
                <div class="bg-gray-50 rounded-xl p-8 shadow-md hover:shadow-xl transition-shadow">
                    <div class="bg-primary bg-opacity-10 text-primary w-16 h-16 rounded-full flex items-center justify-center mb-6 mx-auto">
                        <i class="fas fa-palette text-3xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3 text-center">Warna Tahan Lama</h3>
                    <p class="text-gray-600 text-center">Proses pewarnaan berkualitas tinggi yang membuat warna tetap cerah meski setelah dicuci berkali-kali.</p>
                </div>
                
                <div class="bg-gray-50 rounded-xl p-8 shadow-md hover:shadow-xl transition-shadow">
                    <div class="bg-primary bg-opacity-10 text-primary w-16 h-16 rounded-full flex items-center justify-center mb-6 mx-auto">
                        <i class="fas fa-ruler-combined text-3xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3 text-center">Ukuran Pas</h3>
                    <p class="text-gray-600 text-center">Didesain dengan ukuran yang tepat sehingga mudah dibentuk dan tidak mudah lepas.</p>
                </div>
                
                <div class="bg-gray-50 rounded-xl p-8 shadow-md hover:shadow-xl transition-shadow">
                    <div class="bg-primary bg-opacity-10 text-primary w-16 h-16 rounded-full flex items-center justify-center mb-6 mx-auto">
                        <i class="fas fa-heart text-3xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3 text-center">Ramah Kulit</h3>
                    <p class="text-gray-600 text-center">Bahan hypoallergenic yang aman untuk kulit sensitif dan tidak menimbulkan iritasi.</p>
                </div>
                
                <div class="bg-gray-50 rounded-xl p-8 shadow-md hover:shadow-xl transition-shadow">
                    <div class="bg-primary bg-opacity-10 text-primary w-16 h-16 rounded-full flex items-center justify-center mb-6 mx-auto">
                        <i class="fas fa-medal text-3xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3 text-center">Kualitas Terjamin</h3>
                    <p class="text-gray-600 text-center">Setiap produk melalui quality control ketat untuk memastikan kualitas terbaik sampai ke tangan Anda.</p>
                </div>
            </div>
            
            <div class="mt-16 text-center">
                <a href="https://nava.orderonline.id/pashmina-premium1" 
                   class="bg-gradient-to-r from-primary to-secondary text-white px-8 py-4 rounded-full font-bold text-lg hover:opacity-90 transition-opacity shadow-lg">
                    <i class="fas fa-shopping-cart mr-2"></i> DAPATKAN SEKARANG - DISKON 40%
                </a>
            </div>
        </div>
    </section>

    <!-- Gallery Section -->
    <section id="gallery" class="py-16 bg-gray-50">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl md:text-4xl font-bold mb-4 font-playfair">Galeri <span class="text-primary">Pashmina Inner Premium</span></h2>
                <p class="text-lg text-gray-600 max-w-3xl mx-auto">Lihat bagaimana Pashmina Inner Premium bisa membuat penampilan Anda lebih anggun dan stylish.</p>
            </div>
            
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
                <div class="gallery-item overflow-hidden rounded-xl shadow-md hover:shadow-xl transition-shadow">
                    <img src="https://cdn.orderonline.id/uploads/images_6473271741261731048.png" 
                         alt="Pashmina Inner Premium - Warna Cream" 
                         class="w-full h-64 object-cover cursor-pointer hover:scale-105 transition-transform duration-300"
                         onclick="openModal('https://cdn.orderonline.id/uploads/images_6473271741261731048.png')">
                    <div class="p-4 bg-white">
                        <h3 class="font-bold">Warna Cream</h3>
                        <p class="text-gray-600 text-sm">Elegant dan cocok untuk semua warna kulit</p>
                    </div>
                </div>
                
                <div class="gallery-item overflow-hidden rounded-xl shadow-md hover:shadow-xl transition-shadow">
                    <img src="https://cdn.orderonline.id/uploads/images_5722951741258877243.png" 
                         alt="Pashmina Inner Premium - Warna Dusty Pink" 
                         class="w-full h-64 object-cover cursor-pointer hover:scale-105 transition-transform duration-300"
                         onclick="openModal('https://cdn.orderonline.id/uploads/images_5722951741258877243.png')">
                    <div class="p-4 bg-white">
                        <h3 class="font-bold">Warna Dusty Pink</h3>
                        <p class="text-gray-600 text-sm">Soft dan feminine untuk penampilan manis</p>
                    </div>
                </div>
                
                <div class="gallery-item overflow-hidden rounded-xl shadow-md hover:shadow-xl transition-shadow">
                    <img src="https://cdn.orderonline.id/uploads/images_1596141741258877348.png" 
                         alt="Pashmina Inner Premium - Warna Taupe" 
                         class="w-full h-64 object-cover cursor-pointer hover:scale-105 transition-transform duration-300"
                         onclick="openModal('https://cdn.orderonline.id/uploads/images_1596141741258877348.png')">
                    <div class="p-4 bg-white">
                        <h3 class="font-bold">Warna Taupe</h3>
                        <p class="text-gray-600 text-sm">Netral dan mudah dipadukan dengan outfit apa pun</p>
                    </div>
                </div>
                
                <div class="gallery-item overflow-hidden rounded-xl shadow-md hover:shadow-xl transition-shadow">
                    <img src="https://cdn.orderonline.id/uploads/images_3881141741258877907.png" 
                         alt="Pashmina Inner Premium - Detail Jahitan" 
                         class="w-full h-64 object-cover cursor-pointer hover:scale-105 transition-transform duration-300"
                         onclick="openModal('https://cdn.orderonline.id/uploads/images_3881141741258877907.png')">
                    <div class="p-4 bg-white">
                        <h3 class="font-bold">Detail Jahitan Premium</h3>
                        <p class="text-gray-600 text-sm">Jahitan rapi dan kuat untuk ketahanan maksimal</p>
                    </div>
                </div>
                
                <div class="gallery-item overflow-hidden rounded-xl shadow-md hover:shadow-xl transition-shadow">
                    <img src="https://images.unsplash.com/photo-1529634319299-54203a7c9b5a?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" 
                         alt="Pashmina Inner Premium - Tampilan Depan" 
                         class="w-full h-64 object-cover cursor-pointer hover:scale-105 transition-transform duration-300"
                         onclick="openModal('https://images.unsplash.com/photo-1529634319299-54203a7c9b5a?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80')">
                    <div class="p-4 bg-white">
                        <h3 class="font-bold">Tampilan Depan</h3>
                        <p class="text-gray-600 text-sm">Rapi dan stylish untuk penampilan profesional</p>
                    </div>
                </div>
                
                <div class="gallery-item overflow-hidden rounded-xl shadow-md hover:shadow-xl transition-shadow">
                    <img src="https://images.unsplash.com/photo-1525507119028-ed4c629a60a3?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" 
                         alt="Pashmina Inner Premium - Tampilan Samping" 
                         class="w-full h-64 object-cover cursor-pointer hover:scale-105 transition-transform duration-300"
                         onclick="openModal('https://images.unsplash.com/photo-1525507119028-ed4c629a60a3?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80')">
                    <div class="p-4 bg-white">
                        <h3 class="font-bold">Tampilan Samping</h3>
                        <p class="text-gray-600 text-sm">Jatuh sempurna untuk siluet yang anggun</p>
                    </div>
                </div>
            </div>
            
            <!-- Image Modal -->
            <div id="image-modal" class="modal fixed inset-0 bg-black bg-opacity-75 flex items-center justify-center z-50 p-4">
                <div class="relative max-w-4xl w-full">
                    <button onclick="closeModal()" class="absolute -top-12 right-0 text-white text-3xl hover:text-gray-300">&times;</button>
                    <img id="modal-image" src="" alt="" class="w-full rounded-lg">
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section id="testimonials" class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl md:text-4xl font-bold mb-4 font-playfair">Apa Kata <span class="text-primary">Pelanggan Kami</span>?</h2>
                <p class="text-lg text-gray-600 max-w-3xl mx-auto">Ribuan wanita sudah merasakan kenyamanan dan keanggunan Pashmina Inner Premium.</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="testimonial-card bg-gray-50 rounded-xl p-6 shadow-md hover:shadow-lg transition-all">
                    <div class="flex items-center mb-4">
                        <img src="https://randomuser.me/api/portraits/women/32.jpg" alt="Testimoni 1" class="w-12 h-12 rounded-full object-cover mr-4">
                        <div>
                            <h4 class="font-bold">Sarah Nurhaliza</h4>
                            <div class="flex text-yellow-400 text-sm">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                            </div>
                        </div>
                    </div>
                    <p class="text-gray-600 mb-4">"Pashmina Inner Premium ini benar-benar nyaman dipakai seharian. Bahannya adem dan tidak gerah sama sekali. Warna juga tidak luntur meski sudah beberapa kali dicuci."</p>
                    <img src="https://cdn.orderonline.id/uploads/images_6473271741261731048.png" alt="Testimoni Produk" class="w-full rounded-lg">
                </div>
                
                <div class="testimonial-card bg-gray-50 rounded-xl p-6 shadow-md hover:shadow-lg transition-all">
                    <div class="flex items-center mb-4">
                        <img src="https://randomuser.me/api/portraits/women/44.jpg" alt="Testimoni 2" class="w-12 h-12 rounded-full object-cover mr-4">
                        <div>
                            <h4 class="font-bold">Dewi Lestari</h4>
                            <div class="flex text-yellow-400 text-sm">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                            </div>
                        </div>
                    </div>
                    <p class="text-gray-600 mb-4">"Saya sudah mencoba banyak merk pashmina, tapi yang ini benar-benar berbeda. Bahannya premium dan jatuhnya sempurna. Cocok untuk acara formal maupun casual."</p>
                    <img src="https://cdn.orderonline.id/uploads/images_5722951741258877243.png" alt="Testimoni Produk" class="w-full rounded-lg">
                </div>
                
                <div class="testimonial-card bg-gray-50 rounded-xl p-6 shadow-md hover:shadow-lg transition-all">
                    <div class="flex items-center mb-4">
                        <img src="https://randomuser.me/api/portraits/women/68.jpg" alt="Testimoni 3" class="w-12 h-12 rounded-full object-cover mr-4">
                        <div>
                            <h4 class="font-bold">Rina Melati</h4>
                            <div class="flex text-yellow-400 text-sm">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star-half-alt"></i>
                            </div>
                        </div>
                    </div>
                    <p class="text-gray-600 mb-4">"Sebagai ibu rumah tangga yang aktif, saya butuh pashmina yang praktis dan nyaman. Pashmina Inner Premium ini jawabannya. Tidak perlu sering-sering diatur ulang dan tetap rapi seharian."</p>
                    <img src="https://cdn.orderonline.id/uploads/images_1596141741258877348.png" alt="Testimoni Produk" class="w-full rounded-lg">
                </div>
            </div>
            
            <div class="mt-12 bg-gradient-blue rounded-xl p-8 text-white">
                <div class="max-w-4xl mx-auto text-center">
                    <h3 class="text-2xl md:text-3xl font-bold mb-4">Sudah Siap Merasakan Kenyamanan Pashmina Inner Premium?</h3>
                    <p class="text-lg mb-6">Jangan lewatkan promo diskon 40% hari ini saja! Stok terbatas.</p>
                    <a href="https://nava.orderonline.id/pashmina-premium1" 
                       class="bg-yellow-400 hover:bg-yellow-500 text-gray-900 font-bold py-3 px-8 rounded-full inline-block transition-colors shadow-lg">
                        <i class="fas fa-shopping-cart mr-2"></i> PESAN SEKARANG
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- FAQ Section -->
    <section id="faq" class="py-16 bg-gray-50">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl md:text-4xl font-bold mb-4 font-playfair">Pertanyaan <span class="text-primary">Yang Sering Diajukan</span></h2>
                <p class="text-lg text-gray-600 max-w-3xl mx-auto">Temukan jawaban atas pertanyaan Anda tentang Pashmina Inner Premium.</p>
            </div>
            
            <div class="max-w-3xl mx-auto">
                <div class="faq-item mb-4 border border-gray-200 rounded-xl overflow-hidden">
                    <button class="faq-question w-full text-left p-6 bg-white hover:bg-gray-50 transition-colors flex justify-between items-center">
                        <span class="font-bold">Apa bahan Pashmina Inner Premium ini?</span>
                        <i class="fas fa-chevron-down transition-transform"></i>
                    </button>
                    <div class="faq-answer bg-white">
                        <div class="p-6 pt-0">
                            <p>Pashmina Inner Premium terbuat dari bahan premium berkualitas tinggi yang lembut, adem, dan tidak menerawang. Bahan ini memiliki sirkulasi udara yang baik sehingga nyaman dipakai seharian.</p>
                        </div>
                    </div>
                </div>
                
                <div class="faq-item mb-4 border border-gray-200 rounded-xl overflow-hidden">
                    <button class="faq-question w-full text-left p-6 bg-white hover:bg-gray-50 transition-colors flex justify-between items-center">
                        <span class="font-bold">Apakah warna akan luntur setelah dicuci?</span>
                        <i class="fas fa-chevron-down transition-transform"></i>
                    </button>
                    <div class="faq-answer bg-white">
                        <div class="p-6 pt-0">
                            <p>Tidak. Kami menggunakan proses pewarnaan berkualitas tinggi yang membuat warna tetap cerah meski setelah dicuci berkali-kali. Untuk perawatan optimal, kami sarankan mencuci dengan tangan menggunakan deterjen lembut.</p>
                        </div>
                    </div>
                </div>
                
                <div class="faq-item mb-4 border border-gray-200 rounded-xl overflow-hidden">
                    <button class="faq-question w-full text-left p-6 bg-white hover:bg-gray-50 transition-colors flex justify-between items-center">
                        <span class="font-bold">Berapa ukuran Pashmina Inner Premium?</span>
                        <i class="fas fa-chevron-down transition-transform"></i>
                    </button>
                    <div class="faq-answer bg-white">
                        <div class="p-6 pt-0">
                            <p>Ukuran standar Pashmina Inner Premium adalah 70cm x 200cm, yang merupakan ukuran ideal untuk berbagai bentuk wajah dan gaya hijab. Ukuran ini memberikan kenyamanan maksimal tanpa mengurangi gaya.</p>
                        </div>
                    </div>
                </div>
                
                <div class="faq-item mb-4 border border-gray-200 rounded-xl overflow-hidden">
                    <button class="faq-question w-full text-left p-6 bg-white hover:bg-gray-50 transition-colors flex justify-between items-center">
                        <span class="font-bold">Bagaimana cara perawatannya?</span>
                        <i class="fas fa-chevron-down transition-transform"></i>
                    </button>
                    <div class="faq-answer bg-white">
                        <div class="p-6 pt-0">
                            <p>Untuk perawatan terbaik:
                                <ul class="list-disc pl-5 mt-2 space-y-1">
                                    <li>Cuci dengan tangan menggunakan air dingin dan deterjen lembut</li>
                                    <li>Jangan menggunakan pemutih</li>
                                    <li>Keringkan dengan cara diangin-anginkan, hindari sinar matahari langsung</li>
                                    <li>Setrika dengan suhu rendah</li>
                                </ul>
                            </p>
                        </div>
                    </div>
                </div>
                
                <div class="faq-item mb-4 border border-gray-200 rounded-xl overflow-hidden">
                    <button class="faq-question w-full text-left p-6 bg-white hover:bg-gray-50 transition-colors flex justify-between items-center">
                        <span class="font-bold">Berapa lama pengiriman biasanya?</span>
                        <i class="fas fa-chevron-down transition-transform"></i>
                    </button>
                    <div class="faq-answer bg-white">
                        <div class="p-6 pt-0">
                            <p>Waktu pengiriman bervariasi tergantung lokasi:
                                <ul class="list-disc pl-5 mt-2 space-y-1">
                                    <li>Jabodetabek: 1-2 hari kerja</li>
                                    <li>Pulau Jawa: 2-3 hari kerja</li>
                                    <li>Luar Jawa: 3-5 hari kerja</li>
                                </ul>
                                Kami menggunakan jasa pengiriman terpercaya untuk memastikan produk sampai dengan aman dan tepat waktu.
                            </p>
                        </div>
                    </div>
                </div>
                
                <div class="faq-item mb-4 border border-gray-200 rounded-xl overflow-hidden">
                    <button class="faq-question w-full text-left p-6 bg-white hover:bg-gray-50 transition-colors flex justify-between items-center">
                        <span class="font-bold">Apakah ada garansi untuk produk ini?</span>
                        <i class="fas fa-chevron-down transition-transform"></i>
                    </button>
                    <div class="faq-answer bg-white">
                        <div class="p-6 pt-0">
                            <p>Ya, kami memberikan garansi 30 hari uang kembali jika produk tidak sesuai dengan deskripsi atau terdapat cacat produksi. Untuk klaim garansi, silakan hubungi customer service kami dengan menyertakan foto produk dan bukti pembelian.</p>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="mt-12 text-center">
                <p class="text-lg mb-6">Masih ada pertanyaan? Hubungi kami via WhatsApp:</p>
                <a href="https://wa.me/6281252255248?text=Saya%20punya%20pertanyaan%20tentang%20Pashmina%20Inner%20Premium" 
                   class="bg-green-500 hover:bg-green-600 text-white font-bold py-3 px-8 rounded-full inline-flex items-center transition-colors shadow-lg">
                    <i class="fab fa-whatsapp mr-2 text-xl"></i> CHAT VIA WHATSAPP
                </a>
            </div>
        </div>
    </section>

    <!-- CTA Section -->
    <section class="py-16 bg-gradient-blue text-white">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-3xl md:text-4xl font-bold mb-6 font-playfair">Jangan Lewatkan <span class="text-yellow-300">Promo Spesial</span> Hari Ini!</h2>
            <p class="text-xl mb-8 max-w-3xl mx-auto">Dapatkan Pashmina Inner Premium dengan diskon 40% hanya untuk 100 pembeli pertama hari ini.</p>
            
            <div class="bg-white bg-opacity-20 backdrop-filter backdrop-blur-sm rounded-xl p-6 inline-block mb-8">
                <div class="flex flex-col sm:flex-row items-center justify-center space-y-4 sm:space-y-0 sm:space-x-8">
                    <div class="text-center">
                        <div class="text-5xl font-bold text-yellow-300" id="countdown-hours-2">12</div>
                        <div class="text-sm">Jam</div>
                    </div>
                    <div class="text-center">
                        <div class="text-5xl font-bold text-yellow-300" id="countdown-minutes-2">00</div>
                        <div class="text-sm">Menit</div>
                    </div>
                    <div class="text-center">
                        <div class="text-5xl font-bold text-yellow-300" id="countdown-seconds-2">00</div>
                        <div class="text-sm">Detik</div>
                    </div>
                </div>
            </div>
            
            <div class="flex flex-col sm:flex-row justify-center space-y-4 sm:space-y-0 sm:space-x-6">
                <a href="https://nava.orderonline.id/pashmina-premium1" 
                   class="bg-yellow-400 hover:bg-yellow-500 text-gray-900 font-bold py-4 px-8 rounded-full text-lg transition-colors shadow-lg">
                    <i class="fas fa-shopping-cart mr-2"></i> BELI SEKARANG - DISKON 40%
                </a>
                <a href="https://wa.me/6281252255248?text=Saya%20mau%20pesan%20Pashmina%20Inner%20Premium" 
                   class="bg-white hover:bg-gray-100 text-primary font-bold py-4 px-8 rounded-full text-lg transition-colors shadow-lg">
                    <i class="fab fa-whatsapp mr-2"></i> KONFIRMASI VIA WA
                </a>
            </div>
            
            <div class="mt-8 flex flex-wrap justify-center items-center gap-4">
                <div class="flex items-center bg-white bg-opacity-20 px-4 py-2 rounded-full">
                    <i class="fas fa-check-circle mr-2"></i> 100% Original
                </div>
                <div class="flex items-center bg-white bg-opacity-20 px-4 py-2 rounded-full">
                    <i class="fas fa-truck mr-2"></i> Gratis Ongkir
                </div>
                <div class="flex items-center bg-white bg-opacity-20 px-4 py-2 rounded-full">
                    <i class="fas fa-shield-alt mr-2"></i> Garansi 30 Hari
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-12">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
                <div>
                    <h3 class="text-2xl font-bold mb-4 font-playfair">PASHMINA INNER PREMIUM</h3>
                    <p class="text-gray-400">Tampil anggun dan percaya diri setiap hari dengan Pashmina Inner Premium, pashmina yang dirancang khusus untuk kenyamanan dan gaya hijabmu.</p>
                </div>
                
                <div>
                    <h4 class="text-lg font-bold mb-4">Tautan Cepat</h4>
                    <ul class="space-y-2">
                        <li><a href="#features" class="text-gray-400 hover:text-white transition-colors">Fitur Produk</a></li>
                        <li><a href="#gallery" class="text-gray-400 hover:text-white transition-colors">Galeri</a></li>
                        <li><a href="#testimonials" class="text-gray-400 hover:text-white transition-colors">Testimoni</a></li>
                        <li><a href="#faq" class="text-gray-400 hover:text-white transition-colors">FAQ</a></li>
                    </ul>
                </div>
                
                <div>
                    <h4 class="text-lg font-bold mb-4">Kontak Kami</h4>
                    <ul class="space-y-2">
                        <li class="flex items-center">
                            <i class="fas fa-phone-alt mr-3 text-gray-400"></i>
                            <a href="tel:+6281252255248" class="text-gray-400 hover:text-white transition-colors">+62 812-5222-5248</a>
                        </li>
                        <li class="flex items-center">
                            <i class="fab fa-whatsapp mr-3 text-gray-400"></i>
                            <a href="https://wa.me/6281252255248" class="text-gray-400 hover:text-white transition-colors">WhatsApp</a>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-envelope mr-3 text-gray-400"></i>
                            <span class="text-gray-400">cs@pashminapremium.com</span>
                        </li>
                    </ul>
                </div>
                
                <div>
                    <h4 class="text-lg font-bold mb-4">Pembayaran</h4>
                    <div class="grid grid-cols-3 gap-2">
                        <div class="bg-white p-2 rounded flex items-center justify-center">
                            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e1/Bank_Central_Asia.svg/1200px-Bank_Central_Asia.svg.png" alt="BCA" class="h-8">
                        </div>
                        <div class="bg-white p-2 rounded flex items-center justify-center">
                            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5c/Bank_Mandiri_logo_2016.svg/1200px-Bank_Mandiri_logo_2016.svg.png" alt="Mandiri" class="h-8">
                        </div>
                        <div class="bg-white p-2 rounded flex items-center justify-center">
                            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5b/BRI_logo.svg/1200px-BRI_logo.svg.png" alt="BRI" class="h-8">
                        </div>
                        <div class="bg-white p-2 rounded flex items-center justify-center">
                            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/ad/Logo_BNI_46.png/640px-Logo_BNI_46.png" alt="BNI" class="h-8">
                        </div>
                        <div class="bg-white p-2 rounded flex items-center justify-center">
                            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/72/Logo_dana_blue.svg/1200px-Logo_dana_blue.svg.png" alt="DANA" class="h-8">
                        </div>
                        <div class="bg-white p-2 rounded flex items-center justify-center">
                            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/77/OVO_Logo.png/640px-OVO_Logo.png" alt="OVO" class="h-8">
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="border-t border-gray-800 mt-12 pt-8 flex flex-col md:flex-row justify-between items-center">
                <p class="text-gray-400 text-sm mb-4 md:mb-0">© 2023 Pashmina Inner Premium. All rights reserved.</p>
                <div class="flex space-x-6">
                    <a href="#" class="text-gray-400 hover:text-white transition-colors"><i class="fab fa-facebook-f"></i></a>
                    <a href="#" class="text-gray-400 hover:text-white transition-colors"><i class="fab fa-instagram"></i></a>
                    <a href="#" class="text-gray-400 hover:text-white transition-colors"><i class="fab fa-tiktok"></i></a>
                </div>
            </div>
        </div>
    </footer>

    <!-- Sticky Order Button for Mobile -->
    <div class="md:hidden fixed bottom-0 left-0 right-0 bg-gradient-to-r from-primary to-secondary text-white py-3 px-6 flex justify-between items-center shadow-lg z-40">
        <div>
            <div class="font-bold">PASHMINA INNER PREMIUM</div>
            <div class="text-sm">Diskon 40% - Rp145,000</div>
        </div>
        <a href="https://nava.orderonline.id/pashmina-premium1" 
           class="bg-yellow-400 hover:bg-yellow-500 text-gray-900 font-bold py-2 px-6 rounded-full text-sm transition-colors">
            BELI SEKARANG
        </a>
    </div>

    <script>
        // Mobile Menu Toggle
        document.getElementById('mobile-menu-button').addEventListener('click', function() {
            const menu = document.getElementById('mobile-menu');
            menu.classList.toggle('hidden');
        });

        // Countdown Timer
        function updateCountdown() {
            const now = new Date();
            const endOfDay = new Date();
            endOfDay.setHours(23, 59, 59, 999);
            
            const diff = endOfDay - now;
            
            const hours = Math.floor((diff % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
            const minutes = Math.floor((diff % (1000 * 60 * 60)) / (1000 * 60));
            const seconds = Math.floor((diff % (1000 * 60)) / 1000);
            
            document.getElementById('countdown-hours').textContent = hours.toString().padStart(2, '0');
            document.getElementById('countdown-minutes').textContent = minutes.toString().padStart(2, '0');
            document.getElementById('countdown-seconds').textContent = seconds.toString().padStart(2, '0');
            
            document.getElementById('countdown-hours-2').textContent = hours.toString().padStart(2, '0');
            document.getElementById('countdown-minutes-2').textContent = minutes.toString().padStart(2, '0');
            document.getElementById('countdown-seconds-2').textContent = seconds.toString().padStart(2, '0');
        }
        
        setInterval(updateCountdown, 1000);
        updateCountdown();

        // Image Modal
        function openModal(imageSrc) {
            const modal = document.getElementById('image-modal');
            const modalImage = document.getElementById('modal-image');
            
            modalImage.src = imageSrc;
            modalImage.alt = 'Pashmina Inner Premium';
            
            modal.classList.add('active');
            document.body.style.overflow = 'hidden';
        }
        
        function closeModal() {
            const modal = document.getElementById('image-modal');
            modal.classList.remove('active');
            document.body.style.overflow = 'auto';
        }
        
        // Close modal when clicking outside the image
        document.getElementById('image-modal').addEventListener('click', function(e) {
            if (e.target === this) {
                closeModal();
            }
        });

        // FAQ Accordion
        const faqItems = document.querySelectorAll('.faq-item');
        
        faqItems.forEach(item => {
            const question = item.querySelector('.faq-question');
            
            question.addEventListener('click', () => {
                // Close all other items
                faqItems.forEach(otherItem => {
                    if (otherItem !== item && otherItem.classList.contains('active')) {
                        otherItem.classList.remove('active');
                        otherItem.querySelector('.faq-question i').classList.remove('fa-chevron-up');
                        otherItem.querySelector('.faq-question i').classList.add('fa-chevron-down');
                    }
                });
                
                // Toggle current item
                item.classList.toggle('active');
                
                const icon = question.querySelector('i');
                if (item.classList.contains('active')) {
                    icon.classList.remove('fa-chevron-down');
                    icon.classList.add('fa-chevron-up');
                } else {
                    icon.classList.remove('fa-chevron-up');
                    icon.classList.add('fa-chevron-down');
                }
            });
        });

        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                
                const targetId = this.getAttribute('href');
                if (targetId === '#') return;
                
                const targetElement = document.querySelector(targetId);
                if (targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop - 80,
                        behavior: 'smooth'
                    });
                    
                    // Close mobile menu if open
                    const mobileMenu = document.getElementById('mobile-menu');
                    if (!mobileMenu.classList.contains('hidden')) {
                        mobileMenu.classList.add('hidden');
                    }
                }
            });
        });

        // Show scroll-to-top button when scrolling down
        window.addEventListener('scroll', function() {
            const scrollToTopBtn = document.getElementById('scroll-to-top');
            if (window.pageYOffset > 300) {
                scrollToTopBtn.classList.remove('hidden');
            } else {
                scrollToTopBtn.classList.add('hidden');
            }
        });
    </script>
</body>
</html>
