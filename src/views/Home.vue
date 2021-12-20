<template>
  <header>
    <div>
      <h1><router-link to="/"><img src="../img/logo.png" alt="shinwa"></router-link></h1>
      <nav class="gnav" style="visibility: visible; z-index: 10;">
        <router-link to="/" class="sp_logo"><img src="../img/logo.png" alt="shinwa"></router-link>
        <!-- カスタムメニュー（グローバルナビ） -->
        <ul class="gnav_list"><li id="menu-item-34"><router-link to="/about/">RECTについて</router-link>
          <ul class="sub-menu">
            <li id="menu-item-32"><router-link to="https://rec-tokyo.net/about/greeting/">ご挨拶</router-link></li>
            <li id="menu-item-37"><router-link to="/about/greeting/#philosophy">企業理念</router-link></li>
            <li id="menu-item-72"><router-link to="/about/member/">メンバー</router-link></li>
            <li id="menu-item-31"><router-link to="https://rec-tokyo.net/about/">会社概要</router-link></li>
            <li id="menu-item-38"><router-link to="/about/#access">アクセス</router-link></li>
          </ul>
        </li>
          <li id="menu-item-29"><router-link to="https://rec-tokyo.net/business/">事業内容</router-link>
            <ul class="sub-menu">
              <li id="menu-item-43"><router-link to="https://rec-tokyo.net/business/case/">事例紹介</router-link></li>
              <li id="menu-item-30"><router-link to="https://rec-tokyo.net/business/opinion/">先生方のお声</router-link></li>
            </ul>
          </li>
          <li id="menu-item-35"><router-link target="_blank" rel="noopener" to="https://en-gage.net/ryudo-saiyo/">採用情報</router-link></li>
        </ul>		<!-- /カスタムメニュー（グローバルナビ） -->
        <ul class="sp_sns">
          <li><router-link to="https://www.facebook.com/%E6%A0%AA%E5%BC%8F%E4%BC%9A%E7%A4%BE%E4%B8%8D%E5%8B%95%E7%94%A3%E3%82%B3%E3%83%B3%E3%82%B5%E3%83%AB%E3%83%86%E3%82%A3%E3%83%B3%E3%82%B0%E6%9D%B1%E4%BA%AC-106344737736717/?modal=admin_todo_tour" target="_blank"><i class="fab fa-facebook"></i></router-link></li>
          <li><router-link to="https://twitter.com/rectokyo" target="_blank"><i class="fab fa-twitter"></i></router-link></li>
          <li><router-link to="https://www.instagram.com/rect_tsu.aa/" target="_blank"><i class="fab fa-instagram"></i></router-link></li>
        </ul>
      </nav>
    </div>
    <div>
      <ul class="head_sns">
        <li><router-link to="https://www.facebook.com/%E6%A0%AA%E5%BC%8F%E4%BC%9A%E7%A4%BE%E4%B8%8D%E5%8B%95%E7%94%A3%E3%82%B3%E3%83%B3%E3%82%B5%E3%83%AB%E3%83%86%E3%82%A3%E3%83%B3%E3%82%B0%E6%9D%B1%E4%BA%AC-106344737736717/?modal=admin_todo_tour" target="_blank"><i class="fab fa-facebook"></i></router-link></li>
        <li><router-link to="https://twitter.com/rectokyo" target="_blank"><i class="fab fa-twitter"></i></router-link></li>
        <li><router-link to="https://www.instagram.com/rect_tsu.aa/" target="_blank"><i class="fab fa-instagram"></i></router-link></li>
      </ul>
      <dl class="head_tel">
        <dt>お電話でのお問い合わせはこちら</dt>
        <dd>
          <p>03-3261-8689</p>
          <span>受付時間：9:00 - 18:00（平日）</span>
        </dd>
      </dl>
      <router-link to="/contact/" class="head_contact"><i class="fas fa-envelope"></i><span>お問い合わせ</span></router-link>
      <button class="sp_menu"><span></span></button>
    </div>
  </header>

  <main>

    <section class="mainvisual"></section>
    <section class="top_about">

      <h2>全ては<br>お客様の<br>ために</h2>
      <div>
        <div></div>
        <div>
          <p>株式会社不動産コンサルティング東京は、<br>
            不動産に関する専門家として、<br>
            質の高いサービスを提供し、お客様の信頼に応えます。<br>
            不動産業界では軽視されていたお客様目線を大切にし、<br>
            「健全な価値観」で不動産に関する問題を解決し、<br>
            すべてのお客様に満足していただける不動産会社を目指します。</p>
          <router-link to="/about/" class="btn">会社概要</router-link>
        </div>
      </div>
    </section>

    <section class="top_business">
      <h2>業務内容</h2>
      <ul>
        <li><router-link to="/business/#business_01"><p>不動産売買</p><img class="img-svg" src="../img/icon_business_01.svg" alt=""></router-link></li>
        <li><router-link to="/business/#business_02"><p>相続・事業継承</p><img src="../img/icon_business_02.svg" alt=""></router-link></li>
        <li><router-link to="/business/#business_03"><p>資産分析</p><img src="../img/icon_business_03.svg" alt=""></router-link></li>
        <li><router-link to="/business/#business_04"><p>不動産投資</p><img src="../img/icon_business_04.svg" alt=""></router-link></li>
        <li><router-link to="/business/#business_05"><p>資産活用</p><img src="../img/icon_business_05.svg" alt=""></router-link></li>
        <li><router-link to="/business/#business_06"><p>権利調整</p><img src="../img/icon_business_06.svg" alt=""></router-link></li>
        <li><router-link to="/business/#business_07"><p>不動産賃貸</p><img src="../img/icon_business_07.svg" alt=""></router-link></li>
      </ul>
    </section>
    <section class="top_column">
      <h2>不動産コラム</h2>
      <ul class="top_column_list">
        <li>
          <router-link to="https://rec-tokyo.net/column/544/">
            <div>
              <span style="background: url(https://rec-tokyo.net/wp/wp-content/uploads/2021/11/トップ画像.jpg) no-repeat center/cover;"></span>
            </div>
            <p>あなたの思いをつなぐ遺言書とは～相続で揉めないための遺言指南～</p>
          </router-link>
        </li>
        <li>
          <router-link to="https://rec-tokyo.net/column/403/">
            <div>
              <span style="background: url(https://rec-tokyo.net/wp/wp-content/uploads/2021/10/任意売却コラム用.jpg) no-repeat center/cover;"></span>
            </div>
            <p>住宅ローンが払えなくなった時の選択肢　不動産の任意売却とは</p>
          </router-link>
        </li>
        <li>
          <router-link to="https://rec-tokyo.net/column/311/">
            <div>
              <span style="background: url(https://rec-tokyo.net/wp/wp-content/uploads/2021/09/公示価格ってなに？トップ画.jpg) no-repeat center/cover;"></span>
            </div>
            <p>公示価格と時価の違いって何？プロに聞いてみよう！</p>
          </router-link>
        </li>
        <li>
          <router-link to="https://rec-tokyo.net/column/164/">
            <div>
              <span style="background: url(https://rec-tokyo.net/wp/wp-content/uploads/2021/06/家と電卓-1.png) no-repeat center/cover;"></span>
            </div>
            <p>不動産売却にはどんな費用がかかる？～不動産のプロが解説！～</p>
          </router-link>
        </li>
      </ul>
      <router-link to="/column/" class="btn">コラム一覧</router-link>
    </section>
    <section class="top_recruit">
      <div>
        <h2>採用情報</h2>
        <p>専門性の高い業務を行なっている当社ですが、<br>
          不動産業界以外から挑戦してくれたメンバーも活躍中。<br>
          皆さんからのチャレンジを、お待ちしています。</p>
        <router-link to="https://en-gage.net/ryudo-saiyo/" target="_blank">詳細を見る</router-link>
      </div>
    </section>
  </main>

  <footer>
    <div class="foot_content">
      <div>
        <router-link to="/" class="foot_logo"><img src="https://rec-tokyo.net/wp/wp-content/themes/rec_tokyo/images/logo_white.svg" alt="株式会社不動産コンサルティング東京"></router-link>
        <p>〒101-0061<br>
          東京都千代田区神田三崎町二丁目4番1号<br>
          TUG-Iビル2F<br>
          TEL : 03-3261-8689<br>
          FAX : 03-3261-8687</p>
        <ul>
          <li><router-link to="https://www.facebook.com/%E6%A0%AA%E5%BC%8F%E4%BC%9A%E7%A4%BE%E4%B8%8D%E5%8B%95%E7%94%A3%E3%82%B3%E3%83%B3%E3%82%B5%E3%83%AB%E3%83%86%E3%82%A3%E3%83%B3%E3%82%B0%E6%9D%B1%E4%BA%AC-106344737736717/?modal=admin_todo_tour" target="_blank"><i class="fab fa-facebook"></i></router-link></li>
          <li><router-link to="https://twitter.com/rect_tokyo" target="_blank"><i class="fab fa-twitter"></i></router-link></li>
          <li><router-link to="https://www.instagram.com/rect_tsu.aa/" target="_blank"><i class="fab fa-instagram"></i></router-link></li>
        </ul>
      </div>
      <div>
        <dl>
          <dt><router-link to="/about/">RECTについて</router-link></dt>
          <dd>
            <ul>
              <li><router-link to="/about/greeting/">ご挨拶</router-link></li>
              <li><router-link to="/about/greeting/#philosophy">企業理念</router-link></li>
              <li><router-link to="/about/member/">メンバー</router-link></li>
              <li><router-link to="/about/">会社概要</router-link></li>
              <li><router-link to="/about/#access">アクセス</router-link></li>
            </ul>
          </dd>
        </dl>
        <dl>
          <dt><router-link to="/business/">業務内容</router-link></dt>
          <dd>
            <ul>
              <li><router-link to="/business/case/">事例紹介</router-link></li>
              <li><router-link to="/business/opinion/">先生方のお声</router-link></li>
            </ul>
          </dd>
          <dt><router-link to="/column/">不動産コラム</router-link></dt>
          <dt><router-link to="https://en-gage.net/ryudo-saiyo/" target="_blank">採用情報</router-link></dt>
        </dl>
        <dl>
          <dt><router-link to="/contact/">お問い合わせ</router-link></dt>
          <dt><router-link to="/privacy/">プライバシーポリシー</router-link></dt>
          <dt><router-link to="https://rec-tokyo.net/home-loan/" target="_blank">住宅ローン返済困難相談センター</router-link></dt>
          <dt><router-link to="https://rec-tokyo.net/souzokufudousan/" target="_blank">相続と不動産の専門家</router-link></dt>
        </dl>
        <dl>
          <dt><router-link to="https://www.vbest-tax.jp/" target="_blank">税理士法人ベリーベスト</router-link></dt>
          <dt>ゆめのインベストメント</dt>
        </dl>
      </div>
    </div>
  </footer>
  <p class="copyright">Copyright &copy; 株式会社不動産コンサルティング東京 All Rights Reserved.</p>
</template>

<script>
export default {
  name: "Home"
}
</script>

<style scoped>

</style>
