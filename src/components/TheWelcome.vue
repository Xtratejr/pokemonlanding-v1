<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
import PokemonMagicList from './PokemonMagicList.vue'
</script>

<template>

<div class="poke-main-wrapper">
  
  <div class="kb-blog-type-grid kb-mg-top-">
    <div class="first">
      <ul>
        <li>
          <div class="poke-card-link kb-mg-bottom-2">
            <a>
              <div>
                <img src="/img/pk-scarlet-violet.jpg" alt="" />
              </div>
              <div>
                <h2>
                  Dive into the Paldean Era of the pokemon TCG with
                  the Scarlet & Violet Expansion
                </h2>
                <p>
                  Powerful new cards and the return of a classic mechanic
                  combine to shake up the competition.
                </p>
              </div>
            </a>
          </div>
        </li>
        <li>
          <div class="poke-card-link">
            <a>
              <div>
                <img src="/img/eui-vgc.jpg" alt="" />
              </div>
              <div>
                <h2>
                  2023 EUIC VGC
                  Roundtable Preview
                </h2>
              </div>
            </a>
          </div>
        </li>
        <li>
          <div class="poke-card-link">
            <a>
              <div>
                <img src="/img/euic.jpg" alt="" />
              </div>
              <div>
                <h2>
                  2023 EUIC Power
                  Rankings
                </h2>
              </div>
            </a>
          </div>
        </li>
      </ul>
    </div>
    <div class="second">
      <ul>
        <li>
          <div class="poke-card-link">
            <a>
              <div>
                <img src="/img/typhlosion-scarlet-violet.jpg" alt="" />
              </div>
              <div>
                <h2>
                  Typlosion is coming to Haunt Tera Raid
                  Battles
                </h2>
              </div>
            </a>
          </div>
        </li>
        <li>
          <div class="poke-card-link poke-side-card-link">
            <a>
              <div>
                <img src="" alt="" />
              </div>
              <div>
                <h2>
                  Pokemon Go Raid Battle
                  Strategy: Landorus
                </h2>
              </div>
            </a>
          </div>
        </li>
        <li>
          <div class="poke-card-link">
            <a>
              <div>
                <img src="" alt="" />
              </div>
              <div>
                <h2>
                  2023 Pokemon Go EUIC Preview 
                </h2>
              </div>
            </a>
          </div>
        </li>
      </ul>
    </div>
  </div>
  <div class="main-banner">
    <img src="/img/pk-scarlet-violet.jpg" alt="" style="width: 100%;"/>
  </div>
</div>

<!--   
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Clientes</template>
    Lista de Clientes, pendientes por atender o en proceso.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Tooling</template>

    This project is served and bundled with
    <a href="https://vitejs.dev/guide/features.html" target="_blank" rel="noopener">Vite</a>. The
    recommended IDE setup is
    <a href="https://code.visualstudio.com/" target="_blank" rel="noopener">VSCode</a> +
    <a href="https://github.com/johnsoncodehk/volar" target="_blank" rel="noopener">Volar</a>. If
    you need to test your components and web pages, check out
    <a href="https://www.cypress.io/" target="_blank" rel="noopener">Cypress</a> and
    <a href="https://on.cypress.io/component" target="_blank">Cypress Component Testing</a>.

    <br />

    More instructions are available in <code>README.md</code>.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Ecosystem</template>

    Get official tools and libraries for your project:
    <a href="https://pinia.vuejs.org/" target="_blank" rel="noopener">Pinia</a>,
    <a href="https://router.vuejs.org/" target="_blank" rel="noopener">Vue Router</a>,
    <a href="https://test-utils.vuejs.org/" target="_blank" rel="noopener">Vue Test Utils</a>, and
    <a href="https://github.com/vuejs/devtools" target="_blank" rel="noopener">Vue Dev Tools</a>. If
    you need more resources, we suggest paying
    <a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">Awesome Vue</a>
    a visit.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Community</template>

    Got stuck? Ask your question on
    <a href="https://chat.vuejs.org" target="_blank" rel="noopener">Vue Land</a>, our official
    Discord server, or
    <a href="https://stackoverflow.com/questions/tagged/vue.js" target="_blank" rel="noopener"
      >StackOverflow</a
    >. You should also subscribe to
    <a href="https://news.vuejs.org" target="_blank" rel="noopener">our mailing list</a> and follow
    the official
    <a href="https://twitter.com/vuejs" target="_blank" rel="noopener">@vuejs</a>
    twitter account for latest news in the Vue world.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Support Vue</template>

    As an independent project, Vue relies on community backing for its sustainability. You can help
    us by
    <a href="https://vuejs.org/sponsor/" target="_blank" rel="noopener">becoming a sponsor</a>.
  </WelcomeItem> -->

</template>
