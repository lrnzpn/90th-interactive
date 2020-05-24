<template>
  <div id="content-wrapper">
    <section ref="animate-0">
      <div id="master" class="center">
        <!-- gdn intro -->
        <transition name="fade" mode="out-in">
          <div id="search" class="center" v-if="active <= 3 && active >= 0">
            <!-- logo -->
            <transition name="fade" mode="out-in">
              <div v-if="active === 2" class="logo-container center">
                <div class="tgdn-icon">
                  <div id="tgdn"></div>
                </div>
              </div>
            </transition>
            <!-- search tgdn -->
            <div class="search-box center">
              <div class="search-wrapper center">
                <div class="icon-container">
                  <div class="icon static-image"></div>
                </div>
                <transition name="fade">
                  <span v-if="active >= 2">THE GUIDON Online</span>
                </transition>
              </div>
            </div>
            <!-- credits -->
            <transition name="fade" mode="out-in">
              <div class="credits-container center" v-if="active === 2">
                <div class="creds-wrapper">
                  <div class="writers">
                    <span>
                      Written by:
                      <br />Jasey C. Cruz and Enrique B. Halili
                    </span>
                  </div>
                  <div class="dd">
                    <span>
                      Interactive by:
                      <br />Tria Gonzales and Miggy Pinaroc
                    </span>
                  </div>
                </div>
              </div>
            </transition>
            <!-- laptop no header -->
            <div id="laptop">
              <transition name="fade" mode="out-in">
                <div class="laptop-wrapper center" v-if="active === 3">
                  <div class="macbook-container">
                    <div id="mac"></div>
                  </div>
                </div>
              </transition>
            </div>
          </div>
        </transition>
        <!-- laptop -->
        <transition name="fade" mode="out-in">
          <div id="laptop" v-if="active <= 7 && active >= 4">
            <!-- laptop w/ header -->
            <transition name="fade" mode="out-in">
              <div class="laptop-wrapper search-header center" v-if="active === 4">
                <div class="macbook-container">
                  <div id="mac-search"></div>
                </div>
              </div>
            </transition>
            <!-- laptop text -->
            <transition name="fade" mode="out-in">
              <div class="laptop-text center" v-if="active === 4">
                <p>
                  FOR 90 years, The GUIDON has committed itself to providing its
                  readers with accurate and engaging content, made accessible
                  through newsstands across the campus. After the publication
                  launched its online platforms in 2008, it has steadily begun
                  to delve into the world of digital journalism. Looking towards
                  the future, The GUIDON hopes to fully transition into an
                  online publication by its 100th year.
                </p>
              </div>
            </transition>
            <transition name="fade" mode="out-in">
              <div class="laptop-text3 center" v-if="active === 5">
                <p>
                  Currently, The GUIDON releases around 2,000 physical copies of
                  its paper each month. While these issues are made available to
                  readers before they are released online, much of the
                  publication’s engagement comes from its digital platforms.
                </p>
              </div>
            </transition>
            <!-- newspaper bg -->
            <transition name="fade" mode="out-in">
              <div class="laptop-text2 center" v-if="active >= 6">
                <p class="white">
                  Currently, The GUIDON releases around
                  <b>2,000 physical copies</b> of its paper each month. While
                  these issues are made available to readers before they are
                  released online, much of the publication’s engagement comes
                  from its digital platforms.
                </p>
              </div>
            </transition>
            <transition name="fade" mode="out-in">
              <div class="newspaper-container" v-if="active >= 6">
                <div id="newspapers">
                  <div class="layer"></div>
                </div>
              </div>
            </transition>
          </div>
        </transition>
        <!-- perks -->
        <transition name="fade" mode="out-in">
          <div id="perks" v-if="active <= 11 && active >= 8">
            <transition name="fade">
              <div class="perks-linear center" v-if="active >= 8 && active <= 9">
                <!-- perks w mobile phone -->
                <transition name="fade" mode="out-in">
                  <div class="perks-container" v-if="active === 8">
                    <div class="perks-text">
                      <div class="perks-txt-wrapper">
                        <span>The perks of going digital</span>
                        <p>
                          According to Editor-in-Chief Alithea C. Soriano,
                          adjusting to the demands of its audience is one of the
                          biggest factors pushing The GUIDON to produce more
                          online multimedia content. She also stresses the
                          importance of moving with the times when it comes to
                          staying relevant to the lifestyle of the readers,
                          especially with the rising demand for easily
                          accessible news amidst the “boom of social media”.
                        </p>
                      </div>
                    </div>
                    <div class="perks-digital">
                      <div id="tgdn-mobile"></div>
                    </div>
                  </div>
                </transition>
                <!-- EIC  -->
                <transition name="fade" mode="out-in">
                  <div class="eic-container" v-if="active === 9">
                    <div class="eic-text">
                      <div class="eic-txt-wrapper">
                        <p>
                          "Publications in general really have to be aware of
                          their target market, or target audience, their
                          readers, their stakeholders. Why? Because writing your
                          stories and the way you disseminate it, the
                          effectiveness or the impact of that is determined by
                          how well you know your readers’ habits."
                        </p>
                        <span>Alithea C. Soriano, Editor-in-Chief</span>
                      </div>
                    </div>
                    <div class="eic-illus">
                      <div id="illustration"></div>
                    </div>
                  </div>
                </transition>
              </div>

              <!-- transition to pros and cons -->
              <div class="pc center" v-if="active >= 10 && active <= 11">
                <transition name="fade" mode="out-in">
                  <div class="sm-container" v-if="active === 10">
                    <div class="sm-txt-wrapper">
                      <p>
                        The GUIDON’s Social Media managers Bryce Rubi and Deana
                        Pagtalunan can attest to the potential of shifting to a
                        fully online platform, serving as first-hand witnesses
                        to just how far online content can reach. As those in
                        charge of monitoring the publication’s social media
                        accounts, they mention the high engagement numbers that
                        posts regarding relevant topics can garner, reaching
                        readers beyond the campus grounds. However, they also
                        point out the unique aspects of print releases that
                        would be left behind if ever this shift ever did occur.
                      </p>
                      <p>
                        In all, members of The GUIDON’s Editorial Board have
                        found that taking the leap towards the all-digital
                        format has a lot of advantages. Yet, the monumental task
                        is not without its drawbacks.
                      </p>
                    </div>
                  </div>
                </transition>
                <transition name="fade" mode="out-in">
                  <div class="pc-container" v-if="active === 11">
                    <div class="pc-txt-wrapper">
                      <p>
                        According to our editors, these are the
                        <b>pros and cons</b> of fully shifting The GUIDON to an
                        online platform:
                      </p>
                    </div>
                  </div>
                </transition>
              </div>
            </transition>
          </div>
        </transition>
        <!-- pros and cons -->
        <transition name="fade" mode="out-in">
          <div id="pros-cons" v-if="active <= 21 && active >= 12">
            <transition name="fade" v-if="active >= 12 && active <= 21">
              <div class="pros center">
                <div class="pros-container">
                  <transition name="fade">
                    <div id="pros" class="center" v-if="active >= 12 && active <= 17">
                      <span>Pros</span>
                    </div>
                  </transition>

                  <transition name="fade">
                    <div id="cons" class="center" v-if="active >= 18">
                      <span>Cons</span>
                    </div>
                  </transition>

                  <!-- content -->
                  <div class="pros-wrapper">
                    <transition name="fade">
                      <div class="pros-txt" v-if="active === 12">
                        <div id="defend" class="gdn-img">
                          <div class="pc-txt center">
                            <span>Content can be released immediately.</span>
                          </div>
                          <div class="img-creds">
                            <span>Photo by Miguel Tarrosa</span>
                          </div>
                        </div>
                      </div>
                    </transition>
                  </div>

                  <!-- articles -->
                  <div class="pros-wrapper">
                    <transition name="fade">
                      <div class="pros-txt" v-if="active === 13">
                        <div id="rally" class="gdn-img">
                          <div class="pc-txt center">
                            <span>
                              Articles remain timely and avoid becoming
                              outdated.
                            </span>
                          </div>
                          <div class="img-creds">
                            <span>Photo by Zach Garcia</span>
                          </div>
                        </div>
                      </div>
                    </transition>
                  </div>

                  <!-- uaap -->
                  <div class="pros-wrapper">
                    <transition name="fade">
                      <div class="pros-txt" v-if="active === 14">
                        <div id="uaap" class="gdn-img">
                          <div class="pc-txt center">
                            <span>Released content spreads faster.</span>
                          </div>
                          <div class="img-creds">
                            <span>Photo by Zoey Ignacio</span>
                          </div>
                        </div>
                      </div>
                    </transition>
                  </div>

                  <!-- rally -->
                  <div class="pros-wrapper">
                    <transition name="fade">
                      <div class="pros-txt" v-if="active === 15">
                        <div id="rally2" class="gdn-img">
                          <div class="pc-txt center">
                            <span>
                              Distribution is more environmentally
                              friendly.
                            </span>
                          </div>
                          <div class="img-creds">
                            <span>Photo by Bruce Ong</span>
                          </div>
                        </div>
                      </div>
                    </transition>
                  </div>

                  <!-- fr jett -->
                  <div class="pros-wrapper">
                    <transition name="fade">
                      <div class="pros-txt" v-if="active === 16">
                        <div id="fr" class="gdn-img">
                          <div class="pc-txt center">
                            <span>
                              More creativity and flexibility in terms of
                              content that can be released.
                            </span>
                          </div>
                          <div class="img-creds">
                            <span>Photo by Bruce Ong</span>
                          </div>
                        </div>
                      </div>
                    </transition>
                  </div>

                  <!-- arms -->
                  <div class="pros-wrapper">
                    <transition name="fade">
                      <div class="pros-txt" v-if="active === 17">
                        <div id="arms" class="gdn-img">
                          <div class="pc-txt center">
                            <span>
                              Articles are more easily archived
                              digitally.
                            </span>
                          </div>
                          <div class="img-creds">
                            <span>Photo by Zach Garcia</span>
                          </div>
                        </div>
                      </div>
                    </transition>
                  </div>

                  <!-- voice -->
                  <div class="cons-wrapper">
                    <transition name="fade">
                      <div class="cons-txt" v-if="active === 18">
                        <div id="voice" class="gdn-img">
                          <div class="pc-txt center">
                            <span>
                              Writers will not feel the gratification of seeing
                              their names on printed newspapers.
                            </span>
                          </div>
                          <div class="img-creds">
                            <span>Photo by Regine Salumbre</span>
                          </div>
                        </div>
                      </div>
                    </transition>
                  </div>

                  <!-- owners -->
                  <div class="cons-wrapper">
                    <transition name="fade">
                      <div class="cons-txt" v-if="active === 19">
                        <div id="owners" class="gdn-img">
                          <div class="pc-txt center">
                            <span>
                              Readers lose the feeling of actually holding a
                              newspaper in hand.
                            </span>
                          </div>
                          <div class="img-creds">
                            <span>Photo by Jason Mariano</span>
                          </div>
                        </div>
                      </div>
                    </transition>
                  </div>

                  <!-- embrace -->
                  <div class="cons-wrapper">
                    <transition name="fade">
                      <div class="cons-txt" v-if="active === 20">
                        <div id="embrace" class="gdn-img">
                          <div class="pc-txt center">
                            <span>
                              The tradition of releasing in print is
                              forgone.
                            </span>
                          </div>
                          <div class="img-creds">
                            <span>Photo by Bruce Ong</span>
                          </div>
                        </div>
                      </div>
                    </transition>
                  </div>

                  <!-- tt -->
                  <div class="cons-wrapper">
                    <transition name="fade">
                      <div class="cons-txt" v-if="active === 21">
                        <div id="tt" class="gdn-img">
                          <div class="pc-txt center">
                            <span>
                              Online articles are not easily accessible for
                              those without social media.
                            </span>
                          </div>
                          <div class="img-creds">
                            <span>Photo by Zoey Ignacio</span>
                          </div>
                        </div>
                      </div>
                    </transition>
                  </div>
                </div>
              </div>
            </transition>
          </div>
        </transition>
        <!-- into the future -->
        <transition name="fade" mode="out-in">
          <div id="future" v-if="active >= 22 && active <= 24">
            <div class="future-container center">
              <div class="screen-container center">
                <div id="screen"></div>
              </div>

              <div class="girl1">
                <div id="girl1" class="illus"></div>
              </div>

              <transition name="fade">
                <div class="man" v-if="active >= 23">
                  <div id="man" class="illus"></div>
                </div>
              </transition>

              <transition name="fade">
                <div class="girl2" v-if="active >= 24">
                  <div id="girl2" class="illus"></div>
                </div>
              </transition>

              <div class="screen-menu center">
                <div
                  class="menu-1 dot"
                  v-if="active === 22"
                  v-bind:style="{ backgroundColor: '#7d7d7d' }"
                ></div>
                <div class="menu-1 dot" v-else></div>
                <div
                  class="menu-2 dot"
                  v-if="active === 23"
                  v-bind:style="{ backgroundColor: '#7d7d7d' }"
                ></div>
                <div class="menu-2 dot" v-else></div>
                <div
                  class="menu-3 dot"
                  v-if="active === 24"
                  v-bind:style="{ backgroundColor: '#7d7d7d' }"
                ></div>
                <div class="menu-3 dot" v-else></div>
              </div>

              <!-- text 1 -->
              <transition name="fade">
                <div class="screen-text-container center" v-if="active === 22">
                  <div class="screen-text">
                    <span>Into the future</span>
                    <p>
                      While there is much excitement surrounding The GUIDON’s
                      future as a fully online publication, Soriano notes that
                      the transition must be gradual and well thought-out.
                      According to her, the first step on this journey, which is
                      currently underway, is to survey readers in order to gauge
                      their reaction to the shift towards online content and
                      remain sensitive to the audience’s preferences.
                    </p>
                    <p>
                      Associate Editor Margarita C. Gonzalez says that it is
                      vital to ensure that staffers are prepared to carry out
                      the transition. This means that writers must be able to
                      both conceptualize content that goes beyond the printed
                      word and execute these concepts through collaboration with
                      design cluster staffers.
                    </p>
                  </div>
                </div>
              </transition>

              <!-- text 2 -->
              <transition name="fade">
                <div class="screen-text-container center" v-if="active === 23">
                  <div class="screen-text">
                    <p>
                      Meanwhile, Design Executive Editor Jason T. Mariano
                      highlights the necessary innovations that need to be made
                      to The GUIDON’s website in order to support the influx of
                      online releases. “Being in this position in the 90th Year,
                      we can lay out the road map to make that happen, … we do
                      not live in a print only era, that is why it calls to a
                      shift to online,” said Mariano.
                    </p>
                    <p>
                      One major focus is the creation of an interactive and
                      dynamic website which is optimized for both desktop and
                      mobile devices. With this, the Digital Development staff
                      will take the lead in coding a website that can host a
                      wide range of multimedia content that the publication
                      plans to release.
                    </p>
                  </div>
                </div>
              </transition>

              <!-- text 3 -->
              <transition name="fade">
                <div class="screen-text-container center" v-if="active === 24">
                  <div class="screen-text">
                    <p>
                      In addition to optimizing The GUIDON’s website, the Design
                      Cluster is also looking towards developing an app which
                      will serve as a hub for all of the publication’s content.
                      This will make it easier for readers to access The
                      GUIDON’s releases. From the perspective of Graphic Design
                      Editor Carmela Masiglat, the app will help increase reader
                      engagement due to its focus on graphics and illustrations,
                      as well as its interactive features.
                    </p>
                  </div>
                </div>
              </transition>
            </div>
          </div>
        </transition>
        <!-- mobile app -->
        <transition name="fade" mode="out-in">
          <div id="mobile" v-if="active >= 25 && active < 26">
            <div class="mobile-container center">
              <!-- header -->
              <div class="app-container center">
                <span @click="resetApp">
                  Click on the red elements to view the future Guidon app
                  features.
                </span>
              </div>
              <!-- phone -->
              <div class="phone-container center">
                <div id="phone"></div>
                <div class="features-wrapper">
                  <div class="live-wrapper">
                    <!-- shift through assets on click -->
                    <transition name="fade">
                      <div class="l-wrapper" v-if="live">
                        <div id="live" @click="clickLive"></div>
                      </div>
                    </transition>

                    <transition name="fade">
                      <div class="l-wrapper" v-if="liveAlpha">
                        <div id="live-alpha" @click="clickLive"></div>
                      </div>
                    </transition>
                  </div>

                  <div class="articles-wrapper">
                    <transition name="fade" mode="out-in">
                      <!-- shift through assets on click -->
                      <div class="s-wrapper" v-if="save">
                        <div id="save" @click="clickSave"></div>
                      </div>
                    </transition>

                    <transition name="fade" mode="out-in">
                      <div class="s-wrapper" v-if="saveAlpha">
                        <div id="save-alpha" @click="clickSave"></div>
                      </div>
                    </transition>
                    <!-- shift through assets on click -->
                    <transition name="fade" mode="out-in">
                      <div class="a-wrapper" v-if="article">
                        <div id="articles" @click="clickArticle"></div>
                      </div>
                    </transition>

                    <transition name="fade" mode="out-in">
                      <div class="a-wrapper" v-if="articleAlpha">
                        <div id="articles-alpha" @click="clickArticle"></div>
                      </div>
                    </transition>
                  </div>

                  <div class="chat-wrapper">
                    <!-- shift through assets on click -->
                    <transition name="fade" mode="out-in">
                      <div class="c-wrapper" v-if="chat">
                        <div id="chat" @click="clickChat"></div>
                      </div>
                    </transition>

                    <transition name="fade" mode="out-in">
                      <div class="c-wrapper" v-if="chatAlpha">
                        <div id="chat-alpha" @click="clickChat"></div>
                      </div>
                    </transition>
                  </div>
                </div>
              </div>
              <!-- accompanying text -->
              <div class="appfeat-container center">
                <div class="live-article-container center">
                  <transition name="fade" mode="out-in">
                    <div class="livestreaming-container" v-if="livestream">
                      <span class="title">Livestreaming</span>
                      <p>
                        "[The GUIDON] does livestreaming ...this might be a good
                        way to get access to watches because you’re going to get
                        that push notification ...Just one tap and you’re
                        watching already."
                      </p>
                      <span class="head">
                        Jacob Uriel R. Quintos, Digital Development
                        Deputy
                      </span>
                    </div>
                  </transition>

                  <transition name="fade" mode="out-in">
                    <div class="breaking-container" v-if="breaking">
                      <span class="title">Breaking Articles</span>
                      <p>
                        "I think one of the main features [is transmitting] all
                        the breaking articles, especially if they are relevant
                        because the [article’s popularity] really depends on
                        relevance."
                      </p>
                      <span class="head">Bryce R. Rubi, Social Media Manager</span>
                    </div>
                  </transition>
                </div>
                <div class="save-chat-container center">
                  <transition name="fade" mode="out-in">
                    <div class="saved-container" v-if="saved">
                      <span class="title">Saved Articles</span>
                      <p>
                        "Having a feature that can save articles, because the
                        website we have now, you can only save it by having the
                        tab open and a lot of our content is timeless in nature"
                      </p>
                      <span class="head">Jason T. Mariano, Design Executive Editor</span>
                    </div>
                  </transition>

                  <transition name="fade" mode="out-in">
                    <div class="forum-container" v-if="forum">
                      <span class="title">Chat Forum</span>
                      <p>
                        "I think it would be good if there was a forum portion.
                        The only time the reader really has something to say is
                        when our work is already done."
                      </p>
                      <span class="head">Carmela Masiglat, Graphic Design Editor</span>
                    </div>
                  </transition>
                </div>
              </div>
            </div>
          </div>
        </transition>
        <!-- app details -->
        <transition name="fade" mode="out-in">
          <div id="details" v-if="active >= 26 && active <= 27">
            <div class="final-txt-container center">
              <div class="ftxt-wrapper">
                <div class="final-txt">
                  <p>
                    The focus on multimedia content will also allow the
                    publication’s Design Cluster to take on a bigger role in
                    pitching and conceptualizing releases. According to Mariano,
                    the Design Cluster staffs—such as Graphic Design and
                    Photos—will be asked to pursue their own stories outside the
                    needs of the Writing Cluster. Included in these plans is a
                    platform for staffers to pitch their own projects in order
                    to push for more online releases.
                  </p>
                  <p>
                    In order to facilitate all these changes, The GUIDON plans
                    to reduce the volume of its print issues, in terms of
                    frequency of releases and overall number and length of
                    articles, according to Soriano and Gonzalez. This move will
                    allow writers, artists, and photographers to focus more on
                    collaborative multimedia content.
                  </p>
                </div>

                <div class="stack-container">
                  <transition name="fade" mode="out-in">
                    <div id="stack" v-if="active === 26"></div>
                  </transition>
                  <transition name="fade" mode="out-in">
                    <div id="comp" v-if="active === 27"></div>
                  </transition>
                </div>
              </div>
            </div>
          </div>
        </transition>

        <!-- FINAL WORDS -->
        <transition name="fade" mode="out-in">
          <div id="final" v-if="active === 28">
            <div class="collage-bg-container">
              <div id="upper"></div>
              <div id="lower"></div>
            </div>
            <div class="final-words-container center">
              <div class="final-words">
                <p>
                  Yet, amidst all the hype about The GUIDON’s digital platform,
                  Soriano and Gonzalez both agree that there will always be a
                  role for print releases, especially for issues that correspond
                  to a specific theme. They believe that special releases have
                  the potential to make more of an impact if they are planned
                  out with a specific purpose in mind.
                </p>
                <p>
                  While social media trends are ever evolving, the printed
                  format remains reliable for its constancy. Soriano states that
                  while online content is currently more preferred, print
                  releases provide a “safety net” and the assurance that the
                  publication is able to release content.
                </p>
              </div>
            </div>
          </div>
        </transition>
      </div>
      <div id="triangle" class="center">
        <transition name="fade" mode="out-in">
          <div
            class="triangle-w"
            v-if="
              (this.active >= 6 && this.active <= 9) ||
                (this.active >= 12 && this.active <= 24)
            "
          ></div>
          <div class="triangle-n" v-else></div>
        </transition>
      </div>
    </section>

    <section ref="animate-1"></section>
    <section ref="animate-2"></section>
    <section ref="animate-3"></section>
    <section ref="animate-4"></section>
    <section ref="animate-5"></section>
    <section ref="animate-6"></section>
    <section ref="animate-7"></section>
    <section ref="animate-8"></section>
    <section ref="animate-9"></section>
    <section ref="animate-10"></section>
    <section ref="animate-11"></section>
    <section ref="animate-12"></section>
    <section ref="animate-13"></section>
    <section ref="animate-14"></section>
    <section ref="animate-15"></section>
    <section ref="animate-16"></section>
    <section ref="animate-17"></section>
    <section ref="animate-18"></section>
    <section ref="animate-19"></section>
    <section ref="animate-20"></section>
    <section ref="animate-21"></section>
    <section ref="animate-22"></section>
    <section ref="animate-23"></section>
    <section ref="animate-24"></section>
    <section ref="animate-25"></section>
    <section ref="animate-26"></section>
    <section ref="animate-27"></section>
    <section ref="animate-28"></section>
  </div>
</template>

<script>
export default {
  data() {
    return {
      active: 0,
      live: true,
      save: true,
      article: true,
      chat: true,
      liveAlpha: false,
      saveAlpha: false,
      articleAlpha: false,
      chatAlpha: false,
      livestream: false,
      breaking: false,
      saved: false,
      forum: false
    };
  },
  methods: {
    // detect active on scroll
    scroll() {
      for (
        let i = 0;
        i < document.getElementsByTagName("section").length;
        i++
      ) {
        let el = this.$refs[`animate-${i}`];
        let rect = el.getBoundingClientRect();
        // eslint-disable-next-line no-console
        console.log(`${i} : ${rect.top}`);
        if (rect.top > 0) {
          this.active = i;
          break;
        }
      }

      // expand gdn online
      if (this.active >= 2 && this.active <= 3) {
        document.querySelector(".search-box").style.width = "100%";
        document.querySelector(".search-box").style.background =
          "linear-gradient(90deg, #173359 0%, #2C4396 100%)";
      } else {
        document.querySelector(".search-box").removeAttribute("style");
      }
    },
    // click events for the mobile
    clickLive: function() {
      // hardcode to avoid overlaps on clicks :D
      this.live = true;
      this.liveAlpha = false;

      this.chat = false;
      this.chatAlpha = true;

      this.save = false;
      this.saveAlpha = true;

      this.article = false;
      this.articleAlpha = true;

      // hardcode text also lol
      this.livestream = true;
      this.breaking = false;
      this.saved = false;
      this.forum = false;
    },
    clickSave: function() {
      this.live = false;
      this.liveAlpha = true;

      this.chat = false;
      this.chatAlpha = true;

      this.save = true;
      this.saveAlpha = false;

      this.article = false;
      this.articleAlpha = true;

      this.livestream = false;
      this.breaking = false;
      this.saved = true;
      this.forum = false;
    },
    clickArticle: function() {
      this.live = false;
      this.liveAlpha = true;

      this.chat = false;
      this.chatAlpha = true;

      this.save = false;
      this.saveAlpha = true;

      this.article = true;
      this.articleAlpha = false;

      this.livestream = false;
      this.breaking = true;
      this.saved = false;
      this.forum = false;
    },
    clickChat: function() {
      this.live = false;
      this.liveAlpha = true;

      this.chat = true;
      this.chatAlpha = false;

      this.save = false;
      this.saveAlpha = true;

      this.article = false;
      this.articleAlpha = true;

      this.livestream = false;
      this.breaking = false;
      this.saved = false;
      this.forum = true;
    },
    resetApp() {
      this.live = true;
      this.liveAlpha = false;

      this.chat = true;
      this.chatAlpha = false;

      this.save = true;
      this.saveAlpha = false;

      this.article = true;
      this.articleAlpha = false;

      this.livestream = false;
      this.breaking = false;
      this.saved = false;
      this.forum = false;
    }
  },
  mounted() {
    window.addEventListener("scroll", this.scroll);
  },
  beforeDestroy() {
    window.removeEventListener("scroll", this.scroll);
  }
};
</script>

<style lang="scss" scoped>
#master {
  height: inherit;
  width: 100%;
}

// SEARCH
#search {
  position: fixed;
  width: 100%;
  height: 100%;
  // TGDN SEARCH
  .search-box {
    border-radius: 10px;
    transition: 0.75s ease all;
    position: fixed;
    z-index: 5;
    background: $navy;
    width: 10vw;
    height: 8vw;
    max-height: 130px;
    max-width: 800px;

    @media screen and (max-width: 991px) {
      width: 12vw;
      height: 10vw;
      max-width: 65vw;
    }

    @media screen and (max-width: 768px) {
      max-width: 70vw;
    }

    @media screen and (max-width: 575px) {
      width: 14vw;
      height: 12vw;
      max-width: 75vw;
    }

    .search-wrapper {
      width: 90%;
      .icon {
        height: 3.5em;
        width: 3.5em;
        display: block;
        background-image: url("../assets/icons/search.png");
        @media screen and (max-width: 768px) {
          height: 2.75em;
          width: 2.75em;
        }

        @media screen and (max-width: 575px) {
          height: 2em;
          width: 2em;
        }

        @media screen and (max-width: 375px) {
          height: 1.5em;
          width: 1.5em;
        }
      }

      span {
        color: white;
        white-space: nowrap;
        margin-left: 5%;
        display: inline-block;
        font-size: $font-size--5 * 3;
        transition: 0.75s ease all;

        @media screen and (max-width: 991px) {
          font-size: $font-size--5 * 2;
        }

        @media screen and (max-width: 768px) {
          $font-size: $font-size--5 * 1.2;
        }

        @media screen and (max-width: 575px) {
          font-size: $font-size--5;
        }
      }
    }
  }

  // LOGO
  .logo-container {
    height: 200px;
    width: 100%;
    position: fixed;
    transition: 0.5s all ease;
    top: 7.5%;

    .tgdn-icon {
      height: 100%;
      width: 100%;
      #tgdn {
        background-size: contain;
        background-position: center;
        background-repeat: no-repeat;
        background-image: url("../assets/icons/02 90th Year Logo (BLUE).png");
        height: 200px;
        width: 100%;

        @media screen and (max-width: 768px) {
          height: 150px;
        }
      }
    }
  }

  // CREDITS
  .credits-container {
    width: 100%;
    position: fixed;
    transition: 0.5s all ease;
    bottom: 7.5%;
    div {
      text-align: center;
      margin: 3% 0;

      span {
        color: $navy;
        font-size: $font-size--7;
        line-height: 1.2em;
        transition: 0.5s all ease;

        @media screen and (max-width: 768px) {
          font-size: $font-size--6;
        }

        @media screen and (max-width: 575px) {
          font-size: $font-size--4;
        }
      }
    }
  }
}

// LAPTOP
#laptop {
  position: fixed;
  width: 100%;
  height: 100%;

  .laptop-wrapper {
    width: 100%;
    height: 100%;

    // img {
    //   width: 100vw;
    //   max-width: 1400px;
    // }

    .macbook-container {
      height: 100%;
      width: 100%;
      #mac {
        background-size: contain;
        background-position: center;
        background-repeat: no-repeat;
        background-image: url("../assets/background/laptop.png");
        width: 100vw;
        max-width: 1400px;
        height: inherit;
      }

      #mac-search {
        background-size: contain;
        background-position: center;
        background-repeat: no-repeat;
        background-image: url("../assets/background/search-laptop.png");
        width: 100vw;
        max-width: 1400px;
        height: inherit;
      }
    }
  }

  .laptop-text {
    position: absolute;
    display: flex;
    z-index: 9;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    top: 0;
    width: 100%;
    height: 100%;

    @media screen and (max-width: 768px) {
      top: 17.5%;
    }

    p {
      color: $navy;
      text-align: justify;
      font-size: $font-size--7;
      width: 70vw;
      max-width: 991px;

      @media screen and (max-width: 1199px) {
        font-size: $font-size--6;
      }

      @media screen and (max-width: 991px) {
        font-size: $font-size--5;
      }

      @media screen and (max-width: 768px) {
        width: 85vw;
      }

      @media screen and (max-width: 575px) {
        font-size: $font-size--4;
      }
    }
  }

  .search-header {
    @media screen and (max-width: 768px) {
      bottom: 17.5%;
    }
  }

  .laptop-text2 {
    position: absolute;
    display: flex;
    z-index: 9;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    top: 0;
    width: 100%;
    height: 100%;

    .white {
      color: $white;
    }

    p {
      color: $navy;
      text-align: justify;
      font-size: $font-size--7;
      width: 70vw;
      max-width: 991px;

      @media screen and (max-width: 1199px) {
        font-size: $font-size--6;
      }

      @media screen and (max-width: 991px) {
        font-size: $font-size--5;
      }

      @media screen and (max-width: 768px) {
        width: 85vw;
      }
    }
  }

  // text changes woop
  .laptop-text3 {
    position: absolute;
    display: flex;
    z-index: 9;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    top: 0;
    width: 100%;
    height: 100%;

    p {
      color: $navy;
      text-align: justify;
      font-size: $font-size--7;
      width: 70vw;
      max-width: 991px;

      @media screen and (max-width: 1199px) {
        font-size: $font-size--6;
      }

      @media screen and (max-width: 991px) {
        font-size: $font-size--5;
      }

      @media screen and (max-width: 768px) {
        width: 85vw;
      }
    }
  }

  // NEWSPAPERS
  .newspaper-container {
    height: 100vh;
    width: 100vw;
    position: absolute;
    #newspapers {
      height: 100vh;
      background-image: url("../assets/background/Newspapers.png");
      background-repeat: no-repeat;
      background-size: cover;
      background-position: center;

      .layer {
        width: 100%;
        height: 100%;
        background-color: rgba(23, 51, 89, 0.8);
      }
    }
  }
}

// DIGITAL PERKS
#perks {
  position: fixed;
  width: 100%;
  height: 100%;

  // apply gradient to screen
  .perks-linear {
    height: 100%;
    background: linear-gradient(
      180deg,
      rgba(44, 67, 150, 0.97) 0%,
      #173359 100%
    );
  }

  .perks-container {
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    flex-direction: row;
    height: 100%;
    width: 85%;
    max-width: 1400px;
    margin: 0 auto;
    position: absolute;

    @media screen and (max-width: 768px) {
      flex-direction: column;
    }

    .perks-text {
      width: 60vw;
      text-align: justify;
      color: $white;
      display: flex;
      justify-content: center;
      align-items: flex-end;
      line-height: 3em;

      @media screen and (max-width: 1199px) {
        width: 50vw;
        line-height: 2em;
      }

      @media screen and (max-width: 768px) {
        height: 100%;
        width: 100%;
      }

      @media screen and (max-width: 575px) {
        line-height: 1.5em;
      }

      span {
        font-weight: bold;
        font-size: $font-size--7;

        @media screen and (max-width: 1199px) {
          font-size: $font-size--6;
        }

        @media screen and (max-width: 575px) {
          font-size: $font-size--5;
        }

        @media screen and (max-width: 425px) {
          font-size: $font-size--4;
        }
      }

      p {
        font-size: $font-size--7;
        @media screen and (max-width: 1199px) {
          font-size: $font-size--6;
        }
        @media screen and (max-width: 575px) {
          font-size: $font-size--5;
        }

        @media screen and (max-width: 425px) {
          font-size: $font-size--4;
        }
      }
    }

    .perks-digital {
      width: 40vw;
      height: 100%;
      margin-left: 3%;

      @media screen and (max-width: 1199px) {
        width: 50vw;
      }

      @media screen and (max-width: 768px) {
        width: 100%;
        margin-left: 0;
      }

      #tgdn-mobile {
        height: 100%;
        background-image: url("../assets/background/guidon-min.gif");
        background-repeat: no-repeat;
        background-size: contain;
        background-position: bottom;
      }
    }
  }

  .eic-container {
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    flex-direction: row;
    height: 100%;
    width: 85%;
    max-width: 1400px;
    margin: 0 auto;
    position: absolute;

    @media screen and (max-width: 768px) {
      flex-direction: column;
    }

    .eic-text {
      width: 50vw;
      text-align: justify;
      color: $white;
      display: flex;
      justify-content: center;
      align-items: flex-end;
      line-height: 3.5em;

      @media screen and (max-width: 1199px) {
        line-height: 3em;
      }

      @media screen and (max-width: 768px) {
        height: 100%;
        width: 100%;
        line-height: 2.5em;
        align-items: center;
      }

      @media screen and (max-width: 575px) {
        line-height: 2em;
        align-items: flex-end;
      }

      span {
        font-weight: bold;
        font-style: italic;
        font-size: $font-size--7;

        @media screen and (max-width: 1199px) {
          font-size: $font-size--6;
        }

        @media screen and (max-width: 575px) {
          font-size: $font-size--5;
        }

        @media screen and (max-width: 425px) {
          font-size: $font-size--4;
        }
      }

      p {
        font-size: $font-size--7;
        @media screen and (max-width: 1199px) {
          font-size: $font-size--6;
        }
        @media screen and (max-width: 575px) {
          font-size: $font-size--5;
        }

        @media screen and (max-width: 425px) {
          font-size: $font-size--4;
        }
      }
    }

    .eic-illus {
      width: 50vw;
      height: 100%;
      margin-left: 3%;

      @media screen and (max-width: 1199px) {
      }

      @media screen and (max-width: 768px) {
        width: 75%;
        margin-left: 0;
        margin-bottom: 5%;
      }

      #illustration {
        height: 100%;
        background-image: url("../assets/background/Illustartion.png");
        background-repeat: no-repeat;
        background-size: contain;
        background-position: center;
      }
    }
  }

  // pros and cons
  .pc {
    width: 100%;
    height: 100%;
    .sm-container,
    .pc-container {
      position: absolute;
      width: 85%;
      max-width: 1400px;
    }

    .sm-txt-wrapper,
    .pc-txt-wrapper {
      height: inherit;
      p {
        font-size: $font-size--7;
        text-align: justify;
        color: $navy;
        line-height: 1.5em;

        @media screen and (max-width: 1199px) {
          font-size: $font-size--6;
        }
        @media screen and (max-width: 575px) {
          font-size: $font-size--5;
        }
        @media screen and (max-width: 425px) {
          font-size: $font-size--4;
        }
      }
    }

    .pc-txt-wrapper {
      width: 60%;
      margin: 0 auto;
      p {
        text-align: center;
      }

      @media screen and (max-width: 575px) {
        width: 90%;
      }
    }
  }
}

// PROS & CONS
#pros-cons {
  position: fixed;
  width: 100%;
  height: 100%;

  .pros,
  .cons {
    height: 100%;
  }

  // wrappers
  .pros-wrapper,
  .cons-wrapper {
    height: 100%;
    width: 100%;
    display: flex;
    justify-content: flex-end;
    align-items: flex-end;
    position: absolute;
  }

  .pc-txt {
    height: 100%;
    width: 100%;
    position: absolute;
    span {
      font-size: $font-size--8;
      text-align: center;
      width: 95%;

      @media screen and (max-width: 1199px) {
        font-size: $font-size--7;
      }

      @media screen and (max-width: 991px) {
        font-size: $font-size--6;
      }

      @media screen and (max-width: 768px) {
        font-size: $font-size--7;
      }

      @media screen and (max-width: 575px) {
        font-size: $font-size--6;
      }

      @media screen and (max-width: 425px) {
        font-size: $font-size--5;
      }
    }
  }

  .img-creds {
    height: 100%;
    width: 100%;
    position: absolute;
    display: flex;
    justify-content: flex-end;
    align-items: flex-end;
    span {
      padding: 5%;
      color: $black-alpha;
      width: 200px;
      text-align: right;
      @media screen and (max-width: 575px) {
        font-size: $font-size--3;
      }
    }
  }

  .gdn-img {
    height: 100%;
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
  }

  .pros-container,
  .cons-container {
    height: 100%;
    width: 100%;
    display: flex;
    flex-direction: row;

    @media screen and (max-width: 768px) {
      flex-direction: column;
    }
  }

  // pros color gradient
  #pros {
    width: 50vw;
    height: 100%;
    background: linear-gradient(180deg, #3676b8 0%, #0f4073 100%);
    z-index: 9;
    position: absolute;

    @media screen and (max-width: 768px) {
      width: 100%;
      height: 40vh;
    }

    span {
      color: $white;
      font-size: $font-size--6 * 8;

      @media screen and (max-width: 768px) {
        font-size: $font-size--6 * 4;
      }
    }
  }

  // cons color gradient
  #cons {
    width: 50vw;
    height: 100%;
    background: linear-gradient(180deg, #94295c 0%, #51241f 100%);
    z-index: 9;
    position: absolute;

    @media screen and (max-width: 768px) {
      width: 100%;
      height: 40vh;
    }

    span {
      color: $white;
      font-size: $font-size--6 * 8;

      @media screen and (max-width: 768px) {
        font-size: $font-size--6 * 4;
      }
    }
  }

  // cons wrapper + images
  .cons-txt {
    width: 50vw;
    height: 100%;
    @media screen and (max-width: 768px) {
      width: 100%;
      height: 60vh;
    }

    #voice {
      background-image: url("../assets/background/cons/voice.png");
    }

    #owners {
      background-image: url("../assets/background/cons/owners.png");
    }

    #embrace {
      background-image: url("../assets/background/cons/embrace.png");
    }

    #tt {
      background-image: url("../assets/background/cons/tt.png");
    }
  }

  // pros wrapper + images
  .pros-txt {
    width: 50vw;
    height: 100%;
    @media screen and (max-width: 768px) {
      width: 100%;
      height: 60vh;
    }
    #defend {
      background-image: url("../assets/background/pros/defend.png");
    }

    #rally {
      background-image: url("../assets/background/pros/rally.png");
    }

    #uaap {
      background-image: url("../assets/background/pros/uaap.png");
    }

    #rally2 {
      background-image: url("../assets/background/pros/rally2.png");
    }

    #fr {
      background-image: url("../assets/background/pros/frjett.png");
    }

    #arms {
      background-image: url("../assets/background/pros/arms.png");
    }
  }
}

// INTO THE FUTURE
#future {
  position: fixed;
  height: 100%;
  width: 100%;

  .future-container {
    height: 100%;
    width: 100%;
    background: linear-gradient(
      180deg,
      rgba(44, 67, 150, 0.97) 0%,
      #173359 100%
    );

    .screen-container {
      height: 100%;
      width: 100%;

      #screen {
        height: 90vh;
        width: 90vw;
        max-width: 1400px;
        background-image: url("../assets/background/Window.png");
        background-repeat: no-repeat;
        background-position: unset;

        @media screen and (min-width: 1400px) {
          background-position: top center;
        }

        @media screen and (max-width: 1199px) and (max-height: 1366px) and (orientation: portrait) {
          height: 60vh;
        }

        @media screen and (max-width: 768px) {
          height: 90vh;
        }
      }
    }

    .screen-text-container {
      position: absolute;
      width: 100%;
      height: 100%;

      .screen-text {
        width: 85vw;
        max-width: 1200px;
        text-align: justify;
        line-height: 1.5em;

        font-size: $font-size--6;

        @media screen and (max-width: 1199px) {
          font-size: $font-size--5;
        }

        @media screen and (max-width: 575px) {
          font-size: $font-size--4;
          width: 80vw;
        }

        @media screen and (max-width: 425px) {
          font-size: $font-size--3;
        }

        span {
          font-weight: bold;
        }
      }
    }

    .screen-menu {
      position: absolute;
      width: 100px;
      justify-content: space-around;
      bottom: 15%;

      .dot {
        height: 20px;
        width: 20px;
        background: rgba(115, 115, 115, 0.25);
        border-radius: 50%;

        @media screen and (max-width: 768px) {
          height: 15px;
          width: 15px;
        }
      }
    }
  }

  .illus {
    background-repeat: no-repeat;
    background-size: contain;
  }

  .girl1 {
    position: absolute;
    z-index: 9;
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: flex-end;
    align-items: flex-end;

    @media screen and (min-width: 1500px) {
      max-width: 50%;
    }

    #girl1 {
      width: 100%;
      height: 175px;
      background-image: url("../assets/background/Girl.png");
      background-position: left bottom;
      bottom: 3%;
      left: 1.5%;
      transition: all 0.5s;

      @media screen and (max-width: 768px) {
        height: 150px;
        left: 1%;
      }
      @media screen and (max-width: 375px) {
        height: 125px;
      }
    }
  }

  .girl2 {
    position: absolute;
    z-index: 9;
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: flex-end;
    align-items: flex-end;

    @media screen and (min-width: 1500px) {
      max-width: 50%;
    }

    #girl2 {
      width: 100%;
      height: 225px;
      background-image: url("../assets/background/Girl-1.png");
      background-position: 93% bottom;
      bottom: 5%;
      transition: all 0.5s;

      @media screen and (max-width: 768px) {
        height: 200px;
        background-position: 98% bottom;
      }

      @media screen and (max-width: 575px) {
        height: 175px;
        bottom: 10%;
      }

      @media screen and (max-width: 375px) {
        height: 150px;
      }
    }
  }

  .man {
    position: absolute;
    z-index: 9;
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: flex-end;
    align-items: flex-end;

    #man {
      width: 100%;
      height: 200px;
      background-image: url("../assets/background/Man.png");
      background-position: 60% center;
      bottom: 1%;
      transition: all 0.5s;

      @media screen and (max-width: 768px) {
        height: 150px;
        background-position: 70% center;
      }

      @media screen and (max-width: 575px) {
        background-position: 80% center;
      }

      @media screen and (max-width: 375px) {
        background-position: 85% center;
      }
    }
  }
}

// MOBILE PHONE
#mobile {
  position: fixed;
  width: 100%;
  height: 100%;
  z-index: 9;

  .mobile-container {
    height: 100%;
    width: 100%;
    background: linear-gradient(
      180deg,
      rgba(44, 67, 150, 0.97) 0%,
      #173359 100%
    );
    flex-direction: column;

    .app-container {
      width: 100%;
      height: 75%;
      text-align: center;
      align-items: flex-start;
      position: absolute;

      @media screen and (max-width: 768px) {
        height: 100%;
        align-items: center;
      }

      @media screen and (max-width: 1199px) and (max-height: 1366px) and (orientation: portrait) {
        height: 90%;
        align-items: center;
      }

      span {
        color: $white;
        font-size: $font-size--6;
        width: 40%;
        margin: 1.5%;
        z-index: 10;

        @media screen and (max-width: 1199px) {
          width: 50%;
          font-size: $font-size--5;
        }

        @media screen and(max-width: 768px) {
          max-width: 280px;
          color: $red;
          font-weight: bold;
          font-size: $font-size--4;
          top: 10%;
        }

        @media screen and (max-width: 1199px) and (max-height: 1366px) and (orientation: portrait) {
          max-width: 280px;
          color: $red;
          font-weight: bold;
          font-size: $font-size--4;
          top: 10%;
        }

        @media screen and (max-width: 575px) {
          width: 60%;
          font-size: $font-size--3;
        }

        @media screen and (max-width: 425px) {
        }
      }
    }

    // phone container
    .phone-container {
      height: 100%;
      width: 100%;
      align-items: flex-end;
      z-index: 9;

      #phone {
        height: 75vh;
        width: 100%;
        background-image: url("../assets/background/Phone.png");
        background-repeat: no-repeat;
        background-size: contain;
        background-position: bottom;
      }
    }

    // features container inside the phone
    .features-wrapper {
      height: 70vh;
      width: 290px;
      margin: 0 auto;
      position: absolute;
      transition: all 0.5s;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;

      @media screen and (max-width: 575px) {
        width: 270px;
      }

      @media screen and (max-width: 375px) {
        top: 35%;
      }

      .live-wrapper {
        width: 100%;
        height: 20px;

        .l-wrapper {
          height: auto;
          width: 100%;
          position: absolute;
        }

        #live {
          height: 20px;
          background-image: url("../assets/background/phone/Live.png");
          background-repeat: no-repeat;
          background-size: contain;
          background-position: left;
        }

        #live-alpha {
          height: 20px;
          background-image: url("../assets/background/phone/Live-alpha.png");
          background-repeat: no-repeat;
          background-size: contain;
          background-position: left;
        }
      }

      .chat-wrapper {
        width: 100%;
        height: 55px;

        .c-wrapper {
          height: auto;
          width: 100%;
          position: absolute;
        }

        #chat {
          height: 50px;
          background-image: url("../assets/background/phone/Chat.png");
          background-repeat: no-repeat;
          background-size: 100%;
          background-position: center;
        }

        #chat-alpha {
          height: 50px;
          background-image: url("../assets/background/phone/Chat-alpha.png");
          background-repeat: no-repeat;
          background-size: 100%;
          background-position: center;
        }
      }

      .articles-wrapper {
        height: 55%;
        width: 100%;
        margin: 3% 0;

        .a-wrapper,
        .s-wrapper {
          width: 100%;
          height: 100%;
          position: absolute;
        }

        #save {
          height: 40px;
          width: 99%;
          background-image: url("../assets/background/phone/ribbon.png");
          background-repeat: no-repeat;
          background-size: contain;
          background-position: right;
          position: absolute;
          z-index: 9;
        }

        #save-alpha {
          height: 40px;
          width: 99%;
          background-image: url("../assets/background/phone/Save-alpha.png");
          background-repeat: no-repeat;
          background-size: contain;
          background-position: right;
          position: absolute;
          z-index: 8;
        }

        #articles {
          height: 100%;
          width: 100%;
          background-image: url("../assets/background/phone/articles.png");
          background-repeat: no-repeat;
          background-size: cover;
          background-position: center;
        }

        #articles-alpha {
          height: 100%;
          width: 100%;
          background-image: url("../assets/background/phone/Article-alpha.png");
          background-repeat: no-repeat;
          background-size: cover;
          background-position: center;
        }
      }
    }

    // texts that appear on click
    .appfeat-container {
      position: absolute;
      width: 100%;
      height: 100%;
      justify-content: space-between;
      flex-direction: row;

      @media screen and (max-width: 1199px) and (max-height: 1366px) and (orientation: portrait) {
        flex-direction: column;
      }

      @media screen and (max-width: 768px) {
        flex-direction: column;
      }

      .live-article-container,
      .save-chat-container {
        height: 100%;
        width: 35%;

        @media screen and (max-width: 768px) {
          position: absolute;
          width: 100%;
        }

        @media screen and (max-width: 1199px) and (max-height: 1366px) and (orientation: portrait) {
          position: absolute;
          width: 100%;
        }
      }

      .livestreaming-container,
      .breaking-container,
      .saved-container,
      .forum-container {
        position: absolute;
        margin: 10% auto;
        width: 90%;

        @media screen and (max-width: 768px) {
          top: 0;
        }

        @media screen and (max-width: 1199px) and (max-height: 1366px) and (orientation: portrait) {
          top: 0;
        }

        span,
        p {
          color: $white;
          text-align: justify;
          font-size: $font-size--6;

          @media screen and (max-width: 1199px) {
            font-size: $font-size--5;
          }

          @media screen and (max-width: 575px) {
            font-size: $font-size--4;
          }

          @media screen and (max-width: 425px) {
            font-size: $font-size--3;
          }
        }

        span {
          font-weight: bold;
        }

        .head {
          font-style: italic;
        }
      }
    }
  }
}

// final words on d app
#details {
  position: fixed;
  width: 100%;
  height: 100%;

  .final-txt-container {
    height: 100%;
    width: 85%;
    max-width: 1400px;
    margin: 0 auto;

    .ftxt-wrapper {
      width: 100%;
      height: 100%;
      position: absolute;
      display: flex;
      justify-content: space-between;
      flex-direction: row;
      align-items: center;

      @media screen and (max-width: 768px) {
        flex-direction: column-reverse;
      }
    }

    .final-txt {
      width: 55vw;
      text-align: justify;
      line-height: 2.5em;
      @media screen and (max-width: 768px) {
        width: 100%;
        margin: 5% 0;
      }

      @media screen and (max-width: 575px) {
        height: 60%;
      }

      p {
        font-size: $font-size--6;

        @media screen and (max-width: 1199px) {
          font-size: $font-size--5;
        }

        @media screen and (max-width: 768px) {
          font-size: $font-size--4;
          line-height: 2em;
        }

        @media screen and (max-width: 575px) {
          font-size: $font-size--3;
        }
      }
    }

    .stack-container {
      width: 45vw;
      margin-left: 3%;
      height: 100%;

      @media screen and (max-width: 768px) {
        width: 100%;
        margin: 0;
      }

      @media screen and (max-width: 575px) {
        height: 40%;
      }
      #stack {
        height: 100%;
        width: 100%;
        background-image: url("../assets/background/NewspaperStack.png");
        background-repeat: no-repeat;
        background-size: contain;
        background-position: center;
        position: absolute;
      }

      #comp {
        height: 100%;
        width: 100%;
        background-image: url("../assets/background/Comp.png");
        background-repeat: no-repeat;
        background-size: contain;
        background-position: center;
        position: absolute;
      }
    }
  }
}

// final words na talaga
#final {
  position: fixed;
  width: 100%;
  height: 100%;

  .final-words-container {
    height: 100%;
    width: 85%;
    max-width: 1400px;
    margin: 0 auto;

    p {
      font-size: $font-size--7;
      text-align: justify;
      line-height: 1.5em;

      @media screen and (max-width: 1199px) {
        font-size: $font-size--6;
      }

      @media screen and (max-width: 768px) {
        font-size: $font-size--5;
      }

      @media screen and (max-width: 575px) {
        font-size: $font-size--4;
      }
    }
  }

  .collage-bg-container {
    position: absolute;
    width: 100%;
    height: 100%;

    #upper {
      height: 50%;
      background-image: url("../assets/background/UpperCollage.png");
      background-size: contain;
      background-repeat: no-repeat;
      background-position: top;
      bottom: 20%;

      @media screen and (max-width: 768px) {
        bottom: 10%;
      }

      @media screen and (max-width: 575px) {
        bottom: 5%;
      }
    }

    #lower {
      height: 50%;
      background-image: url("../assets/background/LowerCollage.png");
      background-size: contain;
      background-repeat: no-repeat;
      background-position: bottom;
      top: 20%;

      @media screen and (max-width: 768px) {
        top: 10%;
      }

      @media screen and (max-width: 575px) {
        top: 5%;
      }
    }
  }
}
</style>
