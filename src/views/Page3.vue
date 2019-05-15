<template>
  <div class="page3">
    <div class="container">
      <div class="theme1 section1">
        <div class="content-wrapper">
          <div class="title">
            <span class="subtitle">醫材重複使用<br>病患恐有感染風險</span>
          </div>
          <p>國內包括台大等多家醫學中心爆發違規重複使用一次性耗材，但台北榮總安然度過風暴，甚至被喻為醫院感控模範生，原因在於民國84年「瘧疾事件」及91年「心導管事件」，前者甚至造成4人死亡，慘痛教訓讓北榮從此以最高規格檢視醫材。</p>
          <br><br>
        </div>
        <div class="image-wrapper">
          <img src="../../public/images/article-images/index_page3_article_img1.jpg" alt="">
          <div class="discribe">
            手術器材若消毒不完全，可能引發病人交叉感染血液疾病。
          </div>
        </div>
      </div>
      <div class="theme-default section2">
        <div class="content-wrapper">
          <div class="title">
            <span class="title">北榮曾爆瘧疾院感 釀4死</span>
          </div>
          <p>民國84年，北榮爆發瘧疾疫情，6人罹患瘧疾，調查發現，屬於院內感染，感染者均在同一天下午接受電腦斷層掃描檢查，最後其中4人不幸死亡。</p>                             
          <br>                                 
          <p>疫情調查顯示，負責檢查的羅姓醫師當天一早先幫一名從非洲返國、不慎染上瘧疾的患者施打顯影劑，隨著接手的醫師一時不查，繼續使用原本應該拋棄的注射針筒，以致後面6人均感染瘧疾。</p>                                       
          <br>                                
          <p>「這是非常慘痛的教訓」北榮外科 部部主任馬旭說，瘧疾事件那年，他才剛進入醫界不久，記憶深刻。為此，北榮採取高規模院內感控，對於所有拋棄式（手術刀片）、一次性使用的醫材耗材（能量器械），均嚴格執行清點，確實拋棄。</p>   
          <br>
          <p>馬旭強調，重複使用一次性醫材，暗藏許多感染的風險，</p>
          <br>
        </div>
        <div class="content">
          <span class="mark">
              “以能量器械產品來說，因有長管腔設計，結構複雜，很難完全消毒殺菌，其中最怕的就是「狂牛症」，即使透過高溫，也無法殺死普里昂蛋白，恐讓患者暴露在染病風險之中。” 
          </span>
      </div>
      </div>
      
      <div class="theme-default section3">
        <div class="content-wrapper">
          <div class="title">
            <span class="title">政府「核准」用單次 重複用卻不管？</span>
          </div>
          <p>滕西華舉某重複使用的醫材為例，該醫材仿單（使用說明書）上明確寫著「本產品為單次使用器械」，還加註「不可重新滅菌」，警告處甚至寫「本產品為單次使用器械，重新處理或多次使用可能影響產品結構」，代表連製造的廠商都不支持、不建議重複使用，仿單就跟吃藥一樣，若沒有按指示吃，吃錯得自己負責，但病人根本不知道自己用了什麼，用出問題誰要負責？</p>                             
          <br>    
          <img src="../../public/images/article-images/index_page3_article_img2.svg" alt="">
          <br>
          <br>
        </div>
        <div class="content">
          <span class="mark">
              “臨床實驗都認為只能單次，那重複使用的病人是在幫醫材做另一種臨床實驗嗎？” 
          </span>
        </div>
        <br>
        <br>
        <p>滕西華直言，仿單都經過臨床實驗，是醫療體系必須遵守和依循的「聖經」，廠商會寫單次使用一定有其原因，如果真的像醫界說的使用無疑慮，廠商、政府跟醫療體系三方應該要告訴所有病患為什麼可以重複使用，否則所謂的「幫病人省錢」，可能省著省著就省出問題。</p>
        <br>
        <p>滕西華指出，醫材的管理權責在衛福部食藥署，如果經過政府核准的仿單是限單次使用，但醫院卻拿來重複用，「就是違法」，除非有文獻支持該醫材重複使用無疑慮，那政府該做的是請廠商改仿單，而不是讓醫界存在這種模糊地帶。</p>
        <br>
      </div>

      <div class="theme-default">
        <div class="title">
            醫師: 不該拿病患當理由
        </div>
        <p>台灣內視鏡外科理事長、高雄榮總一般外科主任陳以書表示，外科手術器械都有使用建議，部分器械僅限一次性使用，例如自動吻合器、超音波刀等能量器械，如果醫院為了幫經濟較差的病人而重複使用，應走社會救助或醫院救濟管道，而不是讓病人使用「二手醫材」。</p>
        <br>
      </div>
    </div>
    <div class="container">
      <div class="button-wrapper">
        <div class="last-button"  @click="changePage('/2', '/end', 'last')">
          <i class="nav-arrow nav-arrow-left i-arrow4-left"></i>
        </div>
        <div class="next-button"  @click="changePage('/2', '/end', 'next')">
          術前你該如何自保<i class="nav-arrow nav-arrow-right i-arrow4-right"></i>
        </div>
      </div>
      <div class="page-share">
        <i @click="LineShare(href, 3)" class="line i-line"></i><i @click="FacebookShare(href, 3)" class="facebook i-facebook-1"></i>
      </div>
    </div>
  </div>
</template>

<script>
import Utils from 'udn-newmedia-utils'
import paging from '../mixin/paging.js'
import sharing from '../mixin/sharing.js'

export default {
  name: 'page3',
  mixins: [paging, sharing],
  data () {
    return {
      href: 'https://udn.com/upf/newmedia/2019_data/medical_material/'
    }
  },
  props: {
    msg: String
  },
  mounted () {
    this.$emit('changeRoute', this.$route);
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import '../assets/baseSCSS/theme.scss';
.page3 {
  background-color: #333333;
  padding-top: 120px;
  .content {
    line-height: 2;
    .mark {
        color: #333333;
        background-color: white;
    }
  }
  .section3 {
    img {
 
      @media screen and (max-width: 374px) {
        
      }
      @media screen and (min-width: 768px) {

      }
      @media screen and (min-width: 1024px) {

      }
    }
  }
}
</style>
