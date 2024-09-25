## 개발곰의 깃허브 프로필

      <svg
        width="300"
        height="215"
        viewBox="0 0 300 215"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
        role="img"
        aria-labelledby="descId"
      >
        <title id="titleId"></title>
        <desc id="descId"></desc>
        <style>
          .header {
            font: 600 18px 'Segoe UI', Ubuntu, Sans-Serif;
            fill: #2f80ed;
            animation: fadeInAnimation 0.8s ease-in-out forwards;
          }
          @supports(-moz-appearance: auto) {
            /* Selector detects Firefox */
            .header { font-size: 15.5px; }
          }
          
    @keyframes slideInAnimation {
      from {
        width: 0;
      }
      to {
        width: calc(100%-100px);
      }
    }
    @keyframes growWidthAnimation {
      from {
        width: 0;
      }
      to {
        width: 100%;
      }
    }
    .stat {
      font: 600 14px 'Segoe UI', Ubuntu, "Helvetica Neue", Sans-Serif; fill: #434d58;
    }
    @supports(-moz-appearance: auto) {
      /* Selector detects Firefox */
      .stat { font-size:12px; }
    }
    .bold { font-weight: 700 }
    .lang-name {
      font: 400 11px "Segoe UI", Ubuntu, Sans-Serif;
      fill: #434d58;
    }
    .stagger {
      opacity: 0;
      animation: fadeInAnimation 0.3s ease-in-out forwards;
    }
    #rect-mask rect{
      animation: slideInAnimation 1s ease-in-out forwards;
    }
    .lang-progress{
      animation: growWidthAnimation 0.6s ease-in-out forwards;
    }
    

          
      /* Animations */
      @keyframes scaleInAnimation {
        from {
          transform: translate(-5px, 5px) scale(0);
        }
        to {
          transform: translate(-5px, 5px) scale(1);
        }
      }
      @keyframes fadeInAnimation {
        from {
          opacity: 0;
        }
        to {
          opacity: 1;
        }
      }
    
          
        </style>

        

        <rect
          data-testid="card-bg"
          x="0.5"
          y="0.5"
          rx="4.5"
          height="99%"
          stroke="#e4e2e2"
          width="299"
          fill="#fffefe"
          stroke-opacity="1"
        />

        
      <g
        data-testid="card-title"
        transform="translate(25, 35)"
      >
        <g transform="translate(0, 0)">
      <text
        x="0"
        y="0"
        class="header"
        data-testid="header"
      >Most Used Languages</text>
    </g>
      </g>
    

        <g
          data-testid="main-card-body"
          transform="translate(0, 55)"
        >
          
    <svg data-testid="lang-items" x="25">
      
  
      <mask id="rect-mask">
          <rect x="0" y="0" width="250" height="8" fill="white" rx="5"/>
        </mask>
        
        <rect
          mask="url(#rect-mask)"
          data-testid="lang-progress"
          x="0"
          y="0"
          width="117.4"
          height="8"
          fill="#b07219"
        />
      
        <rect
          mask="url(#rect-mask)"
          data-testid="lang-progress"
          x="117.4"
          y="0"
          width="49.88"
          height="8"
          fill="#563d7c"
        />
      
        <rect
          mask="url(#rect-mask)"
          data-testid="lang-progress"
          x="167.28"
          y="0"
          width="27.54"
          height="8"
          fill="#e34c26"
        />
      
        <rect
          mask="url(#rect-mask)"
          data-testid="lang-progress"
          x="194.82"
          y="0"
          width="20.21"
          height="8"
          fill="#0096D8"
        />
      
        <rect
          mask="url(#rect-mask)"
          data-testid="lang-progress"
          x="215.03"
          y="0"
          width="10.1"
          height="8"
          fill="#3572A5"
        />
      
        <rect
          mask="url(#rect-mask)"
          data-testid="lang-progress"
          x="225.13"
          y="0"
          width="18.29"
          height="8"
          fill="#c6538c"
        />
      
        <rect
          mask="url(#rect-mask)"
          data-testid="lang-progress"
          x="233.42"
          y="0"
          width="18.009999999999998"
          height="8"
          fill="#DA5B0B"
        />
      
        <rect
          mask="url(#rect-mask)"
          data-testid="lang-progress"
          x="241.42999999999998"
          y="0"
          width="15.34"
          height="8"
          fill="#f34b7d"
        />
      
        <rect
          mask="url(#rect-mask)"
          data-testid="lang-progress"
          x="246.76999999999998"
          y="0"
          width="13.22"
          height="8"
          fill="#f1e05a"
        />
      
      
    <g transform="translate(0, 25)">
      <g transform="translate(0, 0)"><g transform="translate(0, 0)">
    <g class="stagger" style="animation-delay: 450ms">
      <circle cx="5" cy="6" r="5" fill="#b07219" />
      <text data-testid="lang-name" x="15" y="10" class='lang-name'>
        Java 46.96%
      </text>
    </g>
  </g><g transform="translate(0, 25)">
    <g class="stagger" style="animation-delay: 600ms">
      <circle cx="5" cy="6" r="5" fill="#563d7c" />
      <text data-testid="lang-name" x="15" y="10" class='lang-name'>
        CSS 19.95%
      </text>
    </g>
  </g><g transform="translate(0, 50)">
    <g class="stagger" style="animation-delay: 750ms">
      <circle cx="5" cy="6" r="5" fill="#e34c26" />
      <text data-testid="lang-name" x="15" y="10" class='lang-name'>
        HTML 11.02%
      </text>
    </g>
  </g><g transform="translate(0, 75)">
    <g class="stagger" style="animation-delay: 900ms">
      <circle cx="5" cy="6" r="5" fill="#0096D8" />
      <text data-testid="lang-name" x="15" y="10" class='lang-name'>
        Processing 8.09%
      </text>
    </g>
  </g><g transform="translate(0, 100)">
    <g class="stagger" style="animation-delay: 1050ms">
      <circle cx="5" cy="6" r="5" fill="#3572A5" />
      <text data-testid="lang-name" x="15" y="10" class='lang-name'>
        Python 4.04%
      </text>
    </g>
  </g></g><g transform="translate(150, 0)"><g transform="translate(0, 0)">
    <g class="stagger" style="animation-delay: 450ms">
      <circle cx="5" cy="6" r="5" fill="#c6538c" />
      <text data-testid="lang-name" x="15" y="10" class='lang-name'>
        SCSS 3.32%
      </text>
    </g>
  </g><g transform="translate(0, 25)">
    <g class="stagger" style="animation-delay: 600ms">
      <circle cx="5" cy="6" r="5" fill="#DA5B0B" />
      <text data-testid="lang-name" x="15" y="10" class='lang-name'>
        Jupyter Notebook 3.21%
      </text>
    </g>
  </g><g transform="translate(0, 50)">
    <g class="stagger" style="animation-delay: 750ms">
      <circle cx="5" cy="6" r="5" fill="#f34b7d" />
      <text data-testid="lang-name" x="15" y="10" class='lang-name'>
        C++ 2.13%
      </text>
    </g>
  </g><g transform="translate(0, 75)">
    <g class="stagger" style="animation-delay: 900ms">
      <circle cx="5" cy="6" r="5" fill="#f1e05a" />
      <text data-testid="lang-name" x="15" y="10" class='lang-name'>
        JavaScript 1.29%
      </text>
    </g>
  </g></g>
    </g>
  
    </svg>
  
        </g>
      </svg>
    

\n\n

( 'u' ฅ >> https://pf.kakao.com/_JBgJxj

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=UantumBear&theme=light&layout=compact&langs_count=13)

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FUantumBear&count_bg=%23928ED7&title_bg=%23000000&icon=ghostery.svg&icon_color=%23FFFFFF&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)
