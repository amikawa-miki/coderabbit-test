<template>
  <div class="min-h-screen">
    <!-- Hero Section -->
    <section class="relative overflow-hidden bg-gradient-to-br from-blue-50 via-white to-purple-50">
      <!-- Navigation -->
      <nav class="container mx-auto px-6 py-6">
        <div class="flex items-center justify-between">
          <div class="text-2xl font-bold gradient-text">
            YourBrand
          </div>
          <div class="hidden md:flex space-x-8">
            <a href="#features" class="text-gray-600 hover:text-blue-600 transition">機能</a>
            <a href="#about" class="text-gray-600 hover:text-blue-600 transition">について</a>
            <a href="#pricing" class="text-gray-600 hover:text-blue-600 transition">料金</a>
            <a href="#contact" class="text-gray-600 hover:text-blue-600 transition">お問い合わせ</a>
          </div>
          <button class="bg-blue-600 text-white px-6 py-2 rounded-lg hover:bg-blue-700 transition">
            無料で始める
          </button>
        </div>
      </nav>

      <!-- Hero Content -->
      <div class="container mx-auto px-6 py-20 md:py-32">
        <div class="grid md:grid-cols-2 gap-12 items-center">
          <div>
            <h1 class="text-5xl md:text-6xl font-bold mb-6 leading-tight">
              <span class="gradient-text">革新的な</span><br />
              ソリューションで<br />
              ビジネスを加速
            </h1>
            <p class="text-xl text-gray-600 mb-8">
              最新のテクノロジーを活用して、あなたのビジネスを次のレベルへ。
              シンプルで強力なツールで、生産性を最大化します。
            </p>
            <div class="flex flex-col sm:flex-row gap-4">
              <button class="bg-blue-600 text-white px-8 py-4 rounded-lg text-lg font-semibold hover:bg-blue-700 transition shadow-lg hover:shadow-xl">
                今すぐ始める
              </button>
              <button class="border-2 border-gray-300 text-gray-700 px-8 py-4 rounded-lg text-lg font-semibold hover:border-blue-600 hover:text-blue-600 transition">
                デモを見る
              </button>
            </div>
          </div>
          <div class="relative">
            <div class="w-full h-96 bg-gradient-to-br from-blue-400 to-purple-500 rounded-2xl shadow-2xl transform rotate-3 hover:rotate-0 transition duration-300"></div>
          </div>
        </div>
      </div>

      <!-- Decorative Elements -->
      <div class="absolute top-20 right-10 w-72 h-72 bg-blue-200 rounded-full mix-blend-multiply filter blur-xl opacity-70 animate-blob"></div>
      <div class="absolute top-40 left-10 w-72 h-72 bg-purple-200 rounded-full mix-blend-multiply filter blur-xl opacity-70 animate-blob animation-delay-2000"></div>
    </section>

    <!-- Features Section -->
    <section id="features" class="py-20 bg-white">
      <div class="container mx-auto px-6">
        <div class="text-center mb-16">
          <h2 class="text-4xl font-bold mb-4">強力な機能</h2>
          <p class="text-xl text-gray-600">ビジネスを成功に導く、すべてが揃っています</p>
        </div>
        
        <div class="grid md:grid-cols-3 gap-8">
          <div class="p-8 rounded-xl bg-gradient-to-br from-blue-50 to-white hover:shadow-xl transition duration-300">
            <div class="w-16 h-16 bg-blue-600 rounded-lg flex items-center justify-center mb-6">
              <svg class="w-8 h-8 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path>
              </svg>
            </div>
            <h3 class="text-2xl font-bold mb-4">高速パフォーマンス</h3>
            <p class="text-gray-600">最適化されたアーキテクチャで、驚くほど高速な処理を実現します。</p>
          </div>

          <div class="p-8 rounded-xl bg-gradient-to-br from-purple-50 to-white hover:shadow-xl transition duration-300">
            <div class="w-16 h-16 bg-purple-600 rounded-lg flex items-center justify-center mb-6">
              <svg class="w-8 h-8 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z"></path>
              </svg>
            </div>
            <h3 class="text-2xl font-bold mb-4">セキュリティ第一</h3>
            <p class="text-gray-600">エンタープライズグレードのセキュリティで、データを安全に保護します。</p>
          </div>

          <div class="p-8 rounded-xl bg-gradient-to-br from-pink-50 to-white hover:shadow-xl transition duration-300">
            <div class="w-16 h-16 bg-pink-600 rounded-lg flex items-center justify-center mb-6">
              <svg class="w-8 h-8 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 21a4 4 0 01-4-4V5a2 2 0 012-2h4a2 2 0 012 2v12a4 4 0 01-4 4zm0 0h12a2 2 0 002-2v-4a2 2 0 00-2-2h-2.343M11 7.343l1.657-1.657a2 2 0 012.828 0l2.829 2.829a2 2 0 010 2.828l-8.486 8.485M7 17h.01"></path>
              </svg>
            </div>
            <h3 class="text-2xl font-bold mb-4">簡単カスタマイズ</h3>
            <p class="text-gray-600">直感的なインターフェースで、誰でも簡単にカスタマイズできます。</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Stats Section -->
    <section class="py-20 bg-gradient-to-r from-blue-600 to-purple-600 text-white">
      <div class="container mx-auto px-6">
        <div class="grid md:grid-cols-4 gap-8 text-center">
          <div>
            <div class="text-5xl font-bold mb-2">10K+</div>
            <div class="text-blue-100">アクティブユーザー</div>
          </div>
          <div>
            <div class="text-5xl font-bold mb-2">99.9%</div>
            <div class="text-blue-100">稼働率</div>
          </div>
          <div>
            <div class="text-5xl font-bold mb-2">50+</div>
            <div class="text-blue-100">国で利用</div>
          </div>
          <div>
            <div class="text-5xl font-bold mb-2">24/7</div>
            <div class="text-blue-100">サポート体制</div>
          </div>
        </div>
      </div>
    </section>

    <!-- Pricing Section -->
    <section id="pricing" class="py-20 bg-gray-50">
      <div class="container mx-auto px-6">
        <div class="text-center mb-16">
          <h2 class="text-4xl font-bold mb-4">シンプルな料金プラン</h2>
          <p class="text-xl text-gray-600">あなたのビジネスに最適なプランを選択</p>
        </div>

        <div class="grid md:grid-cols-3 gap-8 max-w-6xl mx-auto">
          <!-- Free Plan -->
          <div class="bg-white p-8 rounded-xl shadow-lg hover:shadow-2xl transition">
            <h3 class="text-2xl font-bold mb-4">スターター</h3>
            <div class="mb-6">
              <span class="text-5xl font-bold">¥0</span>
              <span class="text-gray-600">/月</span>
            </div>
            <ul class="space-y-4 mb-8">
              <li class="flex items-center">
                <svg class="w-5 h-5 text-green-500 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                </svg>
                基本機能
              </li>
              <li class="flex items-center">
                <svg class="w-5 h-5 text-green-500 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                </svg>
                5プロジェクトまで
              </li>
              <li class="flex items-center">
                <svg class="w-5 h-5 text-green-500 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                </svg>
                コミュニティサポート
              </li>
            </ul>
            <button class="w-full py-3 border-2 border-blue-600 text-blue-600 rounded-lg font-semibold hover:bg-blue-600 hover:text-white transition">
              無料で始める
            </button>
          </div>

          <!-- Pro Plan -->
          <div class="bg-gradient-to-br from-blue-600 to-purple-600 p-8 rounded-xl shadow-2xl transform scale-105 text-white">
            <div class="inline-block bg-yellow-400 text-gray-900 px-3 py-1 rounded-full text-sm font-bold mb-4">
              人気
            </div>
            <h3 class="text-2xl font-bold mb-4">プロ</h3>
            <div class="mb-6">
              <span class="text-5xl font-bold">¥2,980</span>
              <span class="text-blue-100">/月</span>
            </div>
            <ul class="space-y-4 mb-8">
              <li class="flex items-center">
                <svg class="w-5 h-5 text-yellow-400 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                </svg>
                すべての機能
              </li>
              <li class="flex items-center">
                <svg class="w-5 h-5 text-yellow-400 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                </svg>
                無制限プロジェクト
              </li>
              <li class="flex items-center">
                <svg class="w-5 h-5 text-yellow-400 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                </svg>
                優先サポート
              </li>
              <li class="flex items-center">
                <svg class="w-5 h-5 text-yellow-400 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                </svg>
                高度な分析
              </li>
            </ul>
            <button class="w-full py-3 bg-white text-blue-600 rounded-lg font-semibold hover:bg-gray-100 transition">
              今すぐ始める
            </button>
          </div>

          <!-- Enterprise Plan -->
          <div class="bg-white p-8 rounded-xl shadow-lg hover:shadow-2xl transition">
            <h3 class="text-2xl font-bold mb-4">エンタープライズ</h3>
            <div class="mb-6">
              <span class="text-5xl font-bold">カスタム</span>
            </div>
            <ul class="space-y-4 mb-8">
              <li class="flex items-center">
                <svg class="w-5 h-5 text-green-500 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                </svg>
                専用サーバー
              </li>
              <li class="flex items-center">
                <svg class="w-5 h-5 text-green-500 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                </svg>
                カスタム統合
              </li>
              <li class="flex items-center">
                <svg class="w-5 h-5 text-green-500 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                </svg>
                専任サポート
              </li>
              <li class="flex items-center">
                <svg class="w-5 h-5 text-green-500 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                </svg>
                SLA保証
              </li>
            </ul>
            <button class="w-full py-3 border-2 border-blue-600 text-blue-600 rounded-lg font-semibold hover:bg-blue-600 hover:text-white transition">
              お問い合わせ
            </button>
          </div>
        </div>
      </div>
    </section>

    <!-- CTA Section -->
    <section id="contact" class="py-20 bg-white">
      <div class="container mx-auto px-6">
        <div class="bg-gradient-to-r from-blue-600 to-purple-600 rounded-2xl p-12 md:p-16 text-center text-white">
          <h2 class="text-4xl md:text-5xl font-bold mb-6">今すぐ始めましょう</h2>
          <p class="text-xl mb-8 text-blue-100 max-w-2xl mx-auto">
            14日間の無料トライアルで、すべての機能をお試しいただけます。
            クレジットカード不要、いつでもキャンセル可能です。
          </p>
          <div class="flex flex-col sm:flex-row gap-4 justify-center">
            <input 
              type="email" 
              placeholder="メールアドレスを入力"
              class="px-6 py-4 rounded-lg text-gray-900 text-lg w-full sm:w-96"
            />
            <button class="bg-white text-blue-600 px-8 py-4 rounded-lg text-lg font-semibold hover:bg-gray-100 transition whitespace-nowrap">
              無料で始める
            </button>
          </div>
        </div>
      </div>
    </section>

    <!-- Company Info & Map Section -->
    <section class="py-20 bg-gray-50">
      <div class="container mx-auto px-6">
        <div class="text-center mb-16">
          <h2 class="text-4xl font-bold mb-4">アクセス</h2>
          <p class="text-xl text-gray-600">お気軽にお越しください</p>
        </div>

        <div class="grid md:grid-cols-2 gap-12 max-w-6xl mx-auto">
          <!-- Company Information -->
          <div class="space-y-6">
            <div class="bg-white p-8 rounded-xl shadow-lg">
              <h3 class="text-2xl font-bold mb-6 text-gray-900">会社情報</h3>
              
              <div class="space-y-4">
                <div class="flex items-start">
                  <div class="w-12 h-12 bg-blue-100 rounded-lg flex items-center justify-center flex-shrink-0 mr-4">
                    <svg class="w-6 h-6 text-blue-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m4-4h1m-1 4h1m-5 10v-5a1 1 0 011-1h2a1 1 0 011 1v5m-4 0h4"></path>
                    </svg>
                  </div>
                  <div>
                    <h4 class="font-semibold text-gray-900 mb-1">会社名</h4>
                    <p class="text-gray-600">株式会社YourBrand</p>
                  </div>
                </div>

                <div class="flex items-start">
                  <div class="w-12 h-12 bg-purple-100 rounded-lg flex items-center justify-center flex-shrink-0 mr-4">
                    <svg class="w-6 h-6 text-purple-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"></path>
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"></path>
                    </svg>
                  </div>
                  <div>
                    <h4 class="font-semibold text-gray-900 mb-1">住所</h4>
                    <p class="text-gray-600">〒100-0001<br />東京都千代田区千代田1-1-1<br />YourBrandビル 5F</p>
                  </div>
                </div>

                <div class="flex items-start">
                  <div class="w-12 h-12 bg-green-100 rounded-lg flex items-center justify-center flex-shrink-0 mr-4">
                    <svg class="w-6 h-6 text-green-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"></path>
                    </svg>
                  </div>
                  <div>
                    <h4 class="font-semibold text-gray-900 mb-1">電話</h4>
                    <p class="text-gray-600">03-1234-5678</p>
                  </div>
                </div>

                <div class="flex items-start">
                  <div class="w-12 h-12 bg-pink-100 rounded-lg flex items-center justify-center flex-shrink-0 mr-4">
                    <svg class="w-6 h-6 text-pink-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path>
                    </svg>
                  </div>
                  <div>
                    <h4 class="font-semibold text-gray-900 mb-1">メール</h4>
                    <p class="text-gray-600">info@yourbrand.co.jp</p>
                  </div>
                </div>

                <div class="flex items-start">
                  <div class="w-12 h-12 bg-yellow-100 rounded-lg flex items-center justify-center flex-shrink-0 mr-4">
                    <svg class="w-6 h-6 text-yellow-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"></path>
                    </svg>
                  </div>
                  <div>
                    <h4 class="font-semibold text-gray-900 mb-1">営業時間</h4>
                    <p class="text-gray-600">平日 9:00 - 18:00<br />（土日祝日は休業）</p>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <!-- Map -->
          <div class="space-y-6">
            <div class="bg-white p-4 rounded-xl shadow-lg">
              <div class="aspect-[4/3] w-full rounded-lg overflow-hidden">
                <!-- Google Maps Embed -->
                <iframe 
                  src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3240.827853576108!2d139.75309931525888!3d35.68123548019392!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x60188bfbd89f700b%3A0x277c49ba34ed38!2z5p2x5Lqs6aeF!5e0!3m2!1sja!2sjp!4v1234567890123!5m2!1sja!2sjp"
                  width="100%" 
                  height="100%" 
                  style="border:0;" 
                  allowfullscreen
                  loading="lazy" 
                  referrerpolicy="no-referrer-when-downgrade"
                  class="rounded-lg"
                ></iframe>
              </div>
            </div>

            <div class="bg-gradient-to-br from-blue-50 to-purple-50 p-6 rounded-xl">
              <h4 class="font-bold text-lg mb-3 text-gray-900">アクセス方法</h4>
              <ul class="space-y-2 text-gray-700">
                <li class="flex items-start">
                  <span class="text-blue-600 mr-2">●</span>
                  <span>東京駅から徒歩5分</span>
                </li>
                <li class="flex items-start">
                  <span class="text-blue-600 mr-2">●</span>
                  <span>大手町駅 C1出口直結</span>
                </li>
                <li class="flex items-start">
                  <span class="text-blue-600 mr-2">●</span>
                  <span>駐車場：ビル地下1階（有料）</span>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-12">
      <div class="container mx-auto px-6">
        <div class="grid md:grid-cols-4 gap-8 mb-8">
          <div>
            <div class="text-2xl font-bold mb-4">YourBrand</div>
            <p class="text-gray-400">革新的なソリューションで、ビジネスを加速させます。</p>
          </div>
          <div>
            <h4 class="font-bold mb-4">製品</h4>
            <ul class="space-y-2 text-gray-400">
              <li><a href="#" class="hover:text-white transition">機能</a></li>
              <li><a href="#" class="hover:text-white transition">料金</a></li>
              <li><a href="#" class="hover:text-white transition">セキュリティ</a></li>
            </ul>
          </div>
          <div>
            <h4 class="font-bold mb-4">会社</h4>
            <ul class="space-y-2 text-gray-400">
              <li><a href="#" class="hover:text-white transition">会社概要</a></li>
              <li><a href="#" class="hover:text-white transition">ブログ</a></li>
              <li><a href="#" class="hover:text-white transition">採用</a></li>
            </ul>
          </div>
          <div>
            <h4 class="font-bold mb-4">サポート</h4>
            <ul class="space-y-2 text-gray-400">
              <li><a href="#" class="hover:text-white transition">ヘルプセンター</a></li>
              <li><a href="#" class="hover:text-white transition">お問い合わせ</a></li>
              <li><a href="#" class="hover:text-white transition">プライバシー</a></li>
            </ul>
          </div>
        </div>
        <div class="border-t border-gray-800 pt-8 text-center text-gray-400">
          <p>&copy; 2025 YourBrand. All rights reserved.</p>
        </div>
      </div>
    </footer>
  </div>
</template>

<script setup lang="ts">
useHead({
  title: 'YourBrand - 革新的なソリューション',
  meta: [
    { name: 'description', content: 'モダンで美しいランディングページ。最新のテクノロジーでビジネスを加速させます。' }
  ]
})
</script>

<style scoped>
@keyframes blob {
  0% {
    transform: translate(0px, 0px) scale(1);
  }
  33% {
    transform: translate(30px, -50px) scale(1.1);
  }
  66% {
    transform: translate(-20px, 20px) scale(0.9);
  }
  100% {
    transform: translate(0px, 0px) scale(1);
  }
}

.animate-blob {
  animation: blob 7s infinite;
}

.animation-delay-2000 {
  animation-delay: 2s;
}
</style>

