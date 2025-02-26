<script>
    import { onMount } from 'svelte';
  
    let scrollY = 0;
    
    onMount(() => {
      const handleScroll = () => {
        scrollY = window.scrollY;
      };
      
      window.addEventListener('scroll', handleScroll);
      
      return () => {
        window.removeEventListener('scroll', handleScroll);
      };
    });
  </script>
  
  <svelte:head>
    <title>Varenya Thaker | Faith Journey</title>
    <meta name="description" content="Reflections on Job and Jesus by Varenya Thaker" />
  </svelte:head>
  
  <main class="container">
    <header class:scrolled={scrollY > 50}>
      <h1>Varenya Thaker</h1>
    </header>
    
    <section class="hero">
      <div class="hero-content">
        <h2>Suffering & Redemption</h2>
        <div class="divider"></div>
        <p class="subtitle">Reflections on Job and Jesus Christ</p>
      </div>
    </section>
    
    <section class="story">
      <div class="story-container">
        <h3>Patience in Suffering, Glory in Redemption</h3>
        
        <p class="date">February 26, 2025</p>
        
        <p>
          The ancient Book of Job and the Gospel narrative of Jesus Christ stand as two pillars of spiritual understanding, separated by centuries yet connected by profound insights into suffering, faith, and divine purpose. As I've journeyed through my own valleys and mountaintops, these sacred stories have become more than historical accounts—they've become lenses through which I interpret existence itself.
        </p>
        
        <h4>The Righteous Man of Uz</h4>
        
        <p>
          Job's story begins in prosperity. "There was a man in the land of Uz whose name was Job, and that man was blameless and upright, one who feared God and turned away from evil." His righteousness was matched by his prosperity—seven sons and three daughters, thousands of livestock, and a reputation as "the greatest of all the people of the east."
        </p>
        
        <p>
          What follows is perhaps literature's most severe test of faith. In the heavenly court, Satan challenges God: does Job fear God for no reason? Would his faithfulness persist if his blessings were stripped away? With divine permission (a troubling concept itself), calamity strikes. Job loses his possessions, his children, and finally his health, reduced to scraping his sores with pottery shards while sitting in ashes.
        </p>
        
        <p>
          The psychological depth of Job's story unfolds through his dialogues with three friends—Eliphaz, Bildad, and Zophar. They represent conventional wisdom: suffering must be punishment for sin. "Remember," says Eliphaz, "who that was innocent ever perished?" Their theology is neat, logical, and ultimately condemned by God himself.
        </p>
        
        <p>
          Job's laments resonate across millennia: "Why did I not die at birth, come out from the womb and expire?" His questions are raw, honest expressions of anguish that challenge simplistic religious explanations. He maintains his innocence while demanding audience with the divine: "Oh, that I knew where I might find him, that I might come even to his seat!"
        </p>
        
        <p>
          What's remarkable isn't just Job's suffering but his refusal to abandoned faith even while questioning it. "Though he slay me, I will hope in him," he declares, articulating the paradox of faith that persists when evidence suggests abandonment.
        </p>
        
        <h4>The Divine Response</h4>
        
        <p>
          God's answer comes not as explanation but as revelation of perspective. Speaking from the whirlwind, God asks: "Where were you when I laid the foundation of the earth?" Through a series of questions about cosmic creation and the natural order, God doesn't justify Job's suffering but places it within a larger context beyond human comprehension.
        </p>
        
        <p>
          This response has troubled readers for centuries. Job receives no explanation for his suffering, no cosmic justice, only the implicit message that divine wisdom operates on scales beyond human understanding. Yet Job finds this sufficient: "I had heard of you by the hearing of the ear, but now my eye sees you; therefore I despise myself, and repent in dust and ashes."
        </p>
        
        <p>
          Though his prosperity is restored—new children, doubled possessions—the narrative leaves us with questions rather than answers. Is suffering meaningless? Is divine justice comprehensible? Can faith persist when understanding fails? These questions echo through spiritual inquiry to this day.
        </p>
        
        <h4>The Man of Sorrows</h4>
        
        <p>
          Centuries later, another figure enters history—Jesus of Nazareth—whose life and teachings would transform understanding of suffering. Isaiah's prophecy seems to connect these narratives: "He was despised and rejected by men, a man of sorrows and acquainted with grief."
        </p>
        
        <p>
          If Job's suffering was inexplicable, Christ's was intentional. "The Son of Man came not to be served but to serve, and to give his life as a ransom for many." Unlike Job, who questioned divine purpose, Jesus embraced it: "Not my will, but yours, be done." This willingness transforms our understanding of suffering—not as arbitrary punishment but as potential pathway to redemption.
        </p>
        
        <p>
          Christ's journey culminates at Golgotha, where human and divine suffering intersect. "My God, my God, why have you forsaken me?" echoes Job's lament, suggesting that divine incarnation includes experiencing divine absence. Yet this moment of utmost desolation becomes, paradoxically, the foundation of hope.
        </p>
        
        <p>
          The resurrection narrative offers what Job never received—vindication within history. If Job's restoration pointed toward divine justice, Christ's resurrection declares it unequivocally. Death, the ultimate symbol of suffering's finality, is overcome. As Paul writes, "Death is swallowed up in victory."
        </p>
        
        <h4>Suffering Transformed</h4>
        
        <p>
          Together, these narratives offer complementary insights. Job teaches honest questioning within faith; Jesus demonstrates redemptive purpose within suffering. Job shows faith persisting without understanding; Jesus reveals divine solidarity with human pain.
        </p>
        
        <p>
          Perhaps most significantly, both narratives challenge the transactional view of suffering that pervaded ancient thought and persists today—the notion that suffering is simply punishment for wrongdoing. Job's friends represented this view; Jesus explicitly rejected it when asked about a man born blind: "It was not that this man sinned, or his parents, but that the works of God might be displayed in him."
        </p>
        
        <p>
          This transformation of suffering's meaning doesn't erase pain or answer every question. The mystery remains. But by placing suffering within narratives of faithfulness rather than punishment, both Job and Jesus offer frameworks for meaning-making amid life's deepest valleys.
        </p>
        
        <h4>Living Between Job and Jesus</h4>
        
        <p>
          We live in the tension between these stories—between Job's unanswered questions and Christ's redemptive answers, between cosmic mystery and incarnate meaning. Our suffering, like Job's, often lacks immediate explanation; our faith, like his, persists through questioning. Yet Christ's example suggests suffering can become transformative when embraced within divine purpose.
        </p>
        
        <p>
          I've found that most meaningful spiritual growth occurs precisely in this tension—when we bring Job's honesty to our pain while embracing Jesus' surrender to larger purpose. Neither toxic positivity nor faithless despair, but truthful hope.
        </p>
        
        <p>
          The scholar Eleonore Stump suggests that Job's story ultimately isn't about answering why suffering exists, but about the possibility of relationship with God amid suffering. Similarly, the resurrection doesn't eliminate suffering but promises ultimate restoration beyond it. Between these poles, we navigate our own stories of loss and redemption.
        </p>
        
        <p>
          The Apostle Paul, who experienced his own catalogue of suffering, articulated this middle path: "We are afflicted in every way, but not crushed; perplexed, but not driven to despair; persecuted, but not forsaken; struck down, but not destroyed." This isn't denial of suffering but transformation of it through persistent faith.
        </p>
        
        <p>
          Perhaps this is why these ancient stories continue to resonate. They don't offer simplistic answers to suffering's deepest questions, but they do provide frameworks for faithfulness within it. Job teaches us to question honestly; Jesus teaches us to surrender trustingly. Together, they invite us into a fully human yet deeply faithful response to life's inevitable valleys.
        </p>
        
        <p>
          As I continue my own journey through light and shadow, I find myself returning to these narratives not for quick answers but for enduring wisdom. In a world still marked by inexplicable suffering, they offer not explanation but companionship—divine presence amid human pain, and the stubborn hope that mourning will eventually give way to dancing.
        </p>
        
        <p class="quote">
          "I know that my redeemer lives, and that in the end he will stand on the earth." — Job 19:25
        </p>
      </div>
    </section>
    
    <footer>
      <p>© {new Date().getFullYear()} Varenya Thaker</p>
    </footer>
  </main>
  
  <style>
    :global(body) {
      margin: 0;
      padding: 0;
      font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
      background-color: #121212;
      color: #e0e0e0;
      line-height: 1.6;
    }
    
    .container {
      display: flex;
      flex-direction: column;
      min-height: 100vh;
    }
    
    header {
      padding: 2rem;
      position: fixed;
      top: 0;
      left: 0;
      right: 0;
      background-color: rgba(18, 18, 18, 0.8);
      backdrop-filter: blur(8px);
      z-index: 10;
      transition: all 0.3s ease;
    }
    
    header.scrolled {
      padding: 1rem 2rem;
      box-shadow: 0 4px 30px rgba(0, 0, 0, 0.1);
    }
    
    h1 {
      font-size: 1.8rem;
      font-weight: 500;
      letter-spacing: -0.5px;
      margin: 0;
      color: #ffffff;
    }
    
    .hero {
      height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 0 2rem;
      background-color: #1a1a1a;
    }
    
    .hero-content {
      text-align: center;
      max-width: 800px;
    }
    
    h2 {
      font-size: 3.5rem;
      font-weight: 700;
      letter-spacing: -1.5px;
      margin: 0;
      color: #ffffff;
    }
    
    .subtitle {
      font-size: 1.2rem;
      color: #999999;
      margin-top: 1rem;
    }
    
    .divider {
      width: 40px;
      height: 4px;
      background-color: #555555;
      margin: 2rem auto;
    }
    
    .story {
      background-color: #121212;
      padding: 6rem 2rem;
    }
    
    .story-container {
      max-width: 700px;
      margin: 0 auto;
    }
    
    h3 {
      font-size: 2.2rem;
      font-weight: 600;
      letter-spacing: -0.5px;
      margin-bottom: 1rem;
      color: #ffffff;
    }
    
    .date {
      color: #777777;
      font-size: 0.9rem;
      margin-bottom: 2rem;
      font-style: italic;
    }
    
    h4 {
      font-size: 1.5rem;
      font-weight: 500;
      color: #cccccc;
      margin-top: 2.5rem;
      margin-bottom: 1.5rem;
    }
    
    p {
      margin-bottom: 1.5rem;
      font-size: 1.1rem;
      color: #b0b0b0;
    }
    
    .quote {
      font-style: italic;
      color: #999999;
      border-left: 3px solid #555555;
      padding-left: 1.5rem;
      margin: 2.5rem 0;
      font-size: 1.3rem;
    }
    
    footer {
      padding: 2rem;
      background-color: #0a0a0a;
      text-align: center;
      margin-top: auto;
    }
    
    footer p {
      margin: 0;
      font-size: 0.9rem;
      color: #666666;
    }
    
    @media (max-width: 768px) {
      h2 {
        font-size: 2.5rem;
      }
      
      .story {
        padding: 4rem 1.5rem;
      }
      
      h3 {
        font-size: 1.8rem;
      }
      
      h4 {
        font-size: 1.3rem;
      }
      
      p {
        font-size: 1rem;
      }
      
      .quote {
        font-size: 1.1rem;
      }
    }
  </style>