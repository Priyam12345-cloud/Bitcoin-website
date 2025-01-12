<template>
  <div class="container-center-horizontal">
    <div class="macbook-pro-14u34-35 screen">
      <div class="flex-col-33">
        <div class="frame-14335-20">
          <div class="place-79 taviraj-medium-white-32px">{{ place1 }}</div>
          <component5 />
          <navbar />
          <avatar :iconfilluserProps="avatarProps.iconfilluserProps" />
          <img
            class="bedtime-15"
            src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/67751f0f11607350f17e4ccd/img/bedtime.svg"
            alt="bedtime"
          />
        </div>
        <div class="flex-row-47">
          <div class="flex-col-34">
            <img
              class="line-7-1"
              src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/67751e82be6ae96930ecd4ea/img/line-7.svg"
              alt="Line 7"
            />
            <div class="frame-14331-14">
              <div class="frame-14329-11"></div>
              <div class="container-580">
                <a href="javascript:history.back()">
                  <div class="component-3-39">
                    <div class="container-581">
                      <div class="place-80 valign-text-middle taviraj-semi-bold-white-16px">{{ place2 }}</div>
                    </div>
                  </div></a
                >
                <div class="group-5">
                  <div class="bitcoinpng-10" :style="{ 'background-image': 'url(' + bitcoinPng1 + ')' }"></div>
                  <div class="heading-1-9">
                    <div class="container-582">
                      <h1 class="title-16 valign-text-middle taviraj-bold-white-40px">{{ title }}</h1>
                    </div>
                  </div>
                </div>
                <div class="container-583">
                  <div class="component-15-1">
                    <div class="frame-14364">
                      <p class="text-74 valign-text-middle taviraj-semi-bold-white-20px">{{ text1 }}</p>
                    </div>
                  </div>
                </div>
              </div>
              <div class="main">
                <div class="container-584">
                  <div class="vertical-border">
                    <div class="nav-breadcrumbs"></div>
                  </div>
                  <div class="overlap-group4-12">
                    <div class="overlap-group5-12">
                      <div class="overlap-group3-19">
                        <div class="vertical-border-1">
                          <div class="container-585">
                            <div class="container-586">
                              <div class="container-569">
                                <div
                                  class="bitcoinpng-11"
                                  :style="{ 'background-image': 'url(' + bitcoinPng2 + ')' }"
                                ></div>
                                <div class="heading-1-10">
                                  <div class="container-587">
                                    <div class="bitcoin-14 valign-text-middle taviraj-bold-white-30px">
                                      {{ bitcoin }}
                                    </div>
                                  </div>
                                </div>
                              </div>
                              <div class="container-588">
                                <div class="container-589">
                                  <div class="text-326 valign-text-middle taviraj-bold-white-36px">{{ text326 }}</div>
                                </div>
                                <div class="container-590">
                                  <container62 :className="container621Props.className" />
                                  <div class="percent-77 valign-text-middle">{{ percent1 }}</div>
                                </div>
                                <div class="container-591">
                                  <container62 :className="container622Props.className" />
                                </div>
                              </div>
                              <div class="container-592">
                                <div class="background">
                                  <div class="gradient"></div>
                                </div>
                                <div class="container-593">
                                  <component15 :children="component151Props.children" />
                                  <div class="x24h-range valign-text-middle taviraj-semi-bold-white-12px">
                                    {{ x24HRange1 }}
                                  </div>
                                  <component15 :children="component152Props.children" />
                                </div>
                              </div>
                            </div>
                            <div class="frame-14355">
                              <div class="frame-14355">
                                <div class="margin-34">
                                  <div class="component-7-17">
                                    <div class="container-594">
                                      <container2 :className="container2Props.className" />
                                      <div class="add-to-portfolio valign-text-middle taviraj-semi-bold-white-14px">
                                        {{ addToPortfolio }}
                                      </div>
                                    </div>
                                  </div>
                                </div>
                                <div class="container-595">
                                  <div class="container-596">
                                    <div class="container-597">
                                      <div class="component-3-40">
                                        <div class="container-570">
                                          <div class="buy-sell valign-text-middle taviraj-semi-bold-black-12px">
                                            {{ buySell }}
                                          </div>
                                        </div>
                                        <margin :component16Props="margin1Props.component16Props" />
                                      </div>
                                    </div>
                                  </div>
                                </div>
                                <div class="container-598">
                                  <div class="container-599">
                                    <div class="container-600">
                                      <div class="component-3-41">
                                        <div class="container-570">
                                          <div class="wallet valign-text-middle taviraj-semi-bold-black-12px">
                                            {{ wallet }}
                                          </div>
                                        </div>
                                        <margin :component16Props="margin2Props.component16Props" />
                                      </div>
                                    </div>
                                  </div>
                                </div>
                              </div>
                            </div>
                          </div>
                        </div>
                        <div class="container-601">
                          <div class="margin-35">
                            <div class="container-602">
                              <div class="container-603">
                                <div class="container-604">
                                  <div class="group-1">
                                    <component8 :children="component8Props.children" />
                                    <component82 :children="component82Props.children" />
                                    <component83 :children="component83Props.children" />
                                  </div>
                                  <div class="group-2">
                                    <component84 />
                                    <component84 :className="component84Props.className" />
                                  </div>
                                </div>
                                <div class="container-605">
                                  <div class="group-3">
                                    <component85 :children="component85Props.children" />
                                    <component86 :children="component861Props.children" />
                                    <component87 :children="component871Props.children" />
                                    <component87 :children="component872Props.children" />
                                    <component86 :children="component862Props.children" />
                                    <component88 :children="component88Props.children" />
                                    <component89 :children="component89Props.children" />
                                    <component810 :container62Props="component810Props.container62Props" />
                                    <component9 :container62Props="component9Props.container62Props" />
                                    <component92 />
                                  </div>
                                </div>
                              </div>
                              <div class="container-606">
                                <div class="container-607">
                                  <div class="container-608">
                                    <div class="component-4-46">
                                      <div class="overlap-group-85">
                                        <img
                                          class="vector-40"
                                          src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/67751e82be6ae96930ecd4ea/img/vector-19.svg"
                                          alt="Vector"
                                        />
                                        <img class="group-4" :src="group1" alt="Group" /><img
                                          class="group-6"
                                          :src="group2"
                                          alt="Group"
                                        /><img class="group-8" :src="group3" alt="Group" /><img
                                          class="group"
                                          :src="group4"
                                          alt="Group"
                                        /><img class="group-11" :src="group5" alt="Group" /><img
                                          class="group"
                                          :src="group6"
                                          alt="Group"
                                        /><img class="group-14" :src="group7" alt="Group" /><img
                                          class="group-15"
                                          :src="group8"
                                          alt="Group"
                                        /><img class="group-16" :src="group9" alt="Group" />
                                        <div class="text-75">{{ text2 }}</div>
                                        <div class="text-76">{{ text3 }}</div>
                                        <div class="text-77">{{ text4 }}</div>
                                        <div class="group-17 inter-normal-black-11-7px">
                                          <div class="text-330">{{ text330 }}</div>
                                          <div class="text-331">{{ text331 }}</div>
                                          <div class="text-3-1">{{ text327 }}</div>
                                          <div class="text-332">{{ text332 }}</div>
                                          <div class="text-3-1">{{ text333 }}</div>
                                          <div class="text-328">{{ text328 }}</div>
                                          <div class="text-334">{{ text334 }}</div>
                                          <div class="text-3-2">{{ text335 }}</div>
                                          <div class="x20-oct">{{ x20Oct }}</div>
                                          <div class="text-336">{{ text336 }}</div>
                                          <div class="text-3-2">{{ text329 }}</div>
                                          <div class="text-3-2">{{ text337 }}</div>
                                        </div>
                                        <div class="group-18 taviraj-medium-white-11-7px">
                                          <div class="number-60">{{ number1 }}</div>
                                          <div class="number-60">{{ number2 }}</div>
                                          <div class="number-60">{{ number3 }}</div>
                                          <div class="number-60">{{ number4 }}</div>
                                          <div class="number-60">{{ number5 }}</div>
                                          <div class="number-60">{{ number6 }}</div>
                                        </div>
                                        <img class="group-19" :src="group10" alt="Group" /><img
                                          class="rupee-382"
                                          src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/677504417b0079982c5b5748/img/rupee-98.svg"
                                          alt="Rupee"
                                        />
                                        <img
                                          class="rupee-383"
                                          src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/677504417b0079982c5b5748/img/rupee-98.svg"
                                          alt="Rupee"
                                        />
                                        <img
                                          class="rupee-384"
                                          src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/677504417b0079982c5b5748/img/rupee-98.svg"
                                          alt="Rupee"
                                        />
                                        <img
                                          class="rupee-385"
                                          src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/677504417b0079982c5b5748/img/rupee-98.svg"
                                          alt="Rupee"
                                        />
                                        <img
                                          class="rupee-386"
                                          src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/677504417b0079982c5b5748/img/rupee-98.svg"
                                          alt="Rupee"
                                        />
                                        <div class="x8100-lakh valign-text-middle taviraj-semi-bold-white-13px">
                                          {{ x8100Lakh }}
                                        </div>
                                        <div class="x8000-lakh valign-text-middle taviraj-semi-bold-white-13px">
                                          {{ x8000Lakh }}
                                        </div>
                                        <div class="x8025-lakh valign-text-middle taviraj-semi-bold-white-13px">
                                          {{ x8025Lakh }}
                                        </div>
                                        <div class="x8050-lakh valign-text-middle taviraj-semi-bold-white-13px">
                                          {{ x8050Lakh }}
                                        </div>
                                        <div class="x8125-lakh valign-text-middle taviraj-semi-bold-white-13px">
                                          {{ x8125Lakh }}
                                        </div>
                                      </div>
                                      <div class="vector-container">
                                        <img class="vector-41" :src="vector2" alt="Vector" /><img
                                          class="vector-42"
                                          :src="vector3"
                                          alt="Vector"
                                        />
                                      </div>
                                    </div>
                                    <div class="paragraph-192">
                                      <div class="x8075-lakh valign-text-middle taviraj-semi-bold-white-13px">
                                        {{ x8075Lakh }}
                                      </div>
                                      <img
                                        class="rupee-387"
                                        src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/677504417b0079982c5b5748/img/rupee-98.svg"
                                        alt="Rupee"
                                      />
                                    </div>
                                  </div>
                                </div>
                              </div>
                            </div>
                          </div>
                          <div class="margin-36">
                            <div class="border-40">
                              <div class="table-6">
                                <div class="header-row">
                                  <cell42 :children="cell421Props.children" />
                                  <div class="cell-97">
                                    <div class="x24h-6 valign-text-middle taviraj-semi-bold-white-lilac-16px">
                                      {{ x24H }}
                                    </div>
                                  </div>
                                  <cell42 :children="cell422Props.children" :className="cell422Props.className" />
                                  <div class="cell-98">
                                    <div class="x14d valign-text-middle taviraj-semi-bold-white-lilac-16px">
                                      {{ x14D }}
                                    </div>
                                  </div>
                                  <div class="cell-99">
                                    <div class="x30d valign-text-middle taviraj-semi-bold-white-lilac-16px">
                                      {{ x30D }}
                                    </div>
                                  </div>
                                  <div class="cell-100">
                                    <div class="x1yr valign-text-middle taviraj-semi-bold-white-lilac-16px">
                                      {{ x1Yr }}
                                    </div>
                                  </div>
                                </div>
                                <div class="body-row">
                                  <x-data
                                    :percent="xData1Props.percent"
                                    :container222Props="xData1Props.container222Props"
                                  />
                                  <div class="data-974">
                                    <container222 :className="container2221Props.className" />
                                    <div class="percent-78 valign-text-middle taviraj-normal-screamin-green-15px">
                                      {{ percent2 }}
                                    </div>
                                  </div>
                                  <x-data
                                    :percent="xData2Props.percent"
                                    :className="xData2Props.className"
                                    :container222Props="xData2Props.container222Props"
                                  />
                                  <div class="data-975">
                                    <container222 :className="container2222Props.className" />
                                    <div class="percent-79 valign-text-middle taviraj-normal-screamin-green-15px">
                                      {{ percent3 }}
                                    </div>
                                  </div>
                                  <div class="data-976">
                                    <container222 :className="container2223Props.className" />
                                    <div class="percent-80 valign-text-middle taviraj-normal-screamin-green-15px">
                                      {{ percent4 }}
                                    </div>
                                  </div>
                                  <div class="data-977">
                                    <container222 :className="container2224Props.className" />
                                    <div class="percent-81 valign-text-middle taviraj-normal-screamin-green-15px">
                                      {{ percent5 }}
                                    </div>
                                  </div>
                                </div>
                              </div>
                            </div>
                          </div>
                        </div>
                        <img
                          class="rupee-388"
                          src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/67751e82be6ae96930ecd4ea/img/rupee.svg"
                          alt="Rupee"
                        />
                        <img
                          class="rupee-389"
                          src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/67751e82be6ae96930ecd4ea/img/rupee-1.svg"
                          alt="Rupee"
                        />
                      </div>
                      <div class="overlap-group2-22">
                        <div class="vertical-border-2">
                          <img
                            class="line-3-2"
                            src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/67751e82be6ae96930ecd4ea/img/line-3.svg"
                            alt="Line 3"
                          />
                          <div class="margin-37">
                            <div class="container-609">
                              <div class="table-body">
                                <div class="row-10">
                                  <div class="cell-94">
                                    <div class="market-cap-7 valign-text-middle taviraj-semi-bold-lemon-15px">
                                      {{ marketCap }}
                                    </div>
                                    <div class="container-571"><container5 /></div>
                                  </div>
                                  <data252 :children="data2521Props.children" />
                                </div>
                                <div class="row-11">
                                  <div class="cell-94">
                                    <div class="fully-diluted-valuation valign-text-middle">
                                      {{ fullyDilutedValuation }}
                                    </div>
                                    <container6 :container5Props="container61Props.container5Props" />
                                  </div>
                                  <data252 :children="data2522Props.children" :className="data2522Props.className" />
                                </div>
                                <div class="row-12">
                                  <div class="cell-94">
                                    <div class="address-80 valign-text-middle taviraj-semi-bold-lemon-15px">
                                      {{ address }}
                                    </div>
                                    <container6
                                      :className="container62Props.className"
                                      :container5Props="container62Props.container5Props"
                                    />
                                  </div>
                                  <div class="data-972">
                                    <div class="text-340 valign-text-middle taviraj-semi-bold-white-14px">
                                      {{ text340 }}
                                    </div>
                                  </div>
                                </div>
                                <div class="row-13">
                                  <div class="cell-94">
                                    <div class="circulating-supply valign-text-middle taviraj-semi-bold-lemon-15px">
                                      {{ circulatingSupply }}
                                    </div>
                                    <container6
                                      :className="container63Props.className"
                                      :container5Props="container63Props.container5Props"
                                    />
                                  </div>
                                  <div class="data-978">
                                    <div class="text-341 valign-text-middle taviraj-semi-bold-white-14px">
                                      {{ text341 }}
                                    </div>
                                  </div>
                                </div>
                                <div class="row-14">
                                  <div class="cell-94">
                                    <div class="total-supply valign-text-middle taviraj-semi-bold-lemon-15px">
                                      {{ totalSupply }}
                                    </div>
                                    <container6
                                      :className="container64Props.className"
                                      :container5Props="container64Props.container5Props"
                                    />
                                  </div>
                                  <data332 />
                                </div>
                                <div class="row-15">
                                  <div class="cell-94">
                                    <div class="name-16 valign-text-middle taviraj-semi-bold-lemon-15px">
                                      {{ name }}
                                    </div>
                                    <div class="container-571">
                                      <container5 :className="container5Props.className" />
                                    </div>
                                  </div>
                                  <data332 />
                                </div>
                              </div>
                              <container7 />
                            </div>
                          </div>
                          <img
                            class="line-29"
                            src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/67751e82be6ae96930ecd4ea/img/line-3.svg"
                            alt="Line 2"
                          />
                          <div class="container-610">
                            <div class="info valign-text-middle taviraj-bold-white-20px">{{ info }}</div>
                          </div>
                          <div class="vertical-border-item">
                            <div class="container-611">
                              <div class="container-612">
                                <div class="margin-33">
                                  <div class="container-572">
                                    <div class="website valign-text-middle taviraj-medium-lemon-14px">
                                      {{ website }}
                                    </div>
                                  </div>
                                </div>
                                <div class="container-573">
                                  <component10 :children="component10Props.children" />
                                  <component102 :children="component102Props.children" />
                                </div>
                              </div>
                              <div class="horizontal-border">
                                <div class="margin-33">
                                  <div class="container-572">
                                    <div class="explorers valign-text-middle taviraj-semi-bold-lemon-14px">
                                      {{ explorers }}
                                    </div>
                                  </div>
                                </div>
                                <div class="container-574">
                                  <div class="container-613">
                                    <component103 :children="component103Props.children" />
                                    <component3 :component16Props="component31Props.component16Props" />
                                  </div>
                                </div>
                              </div>
                              <div class="horizontal-border-1">
                                <div class="margin-33">
                                  <div class="container-572">
                                    <div class="wallets valign-text-middle taviraj-semi-bold-lemon-14px">
                                      {{ wallets }}
                                    </div>
                                  </div>
                                </div>
                                <div class="container-574">
                                  <div class="container-614">
                                    <component104 :container8Props="component104Props.container8Props" />
                                    <component3
                                      :className="component32Props.className"
                                      :component16Props="component32Props.component16Props"
                                    />
                                  </div>
                                </div>
                              </div>
                              <div class="horizontal-border">
                                <div class="margin-33">
                                  <div class="container-572">
                                    <div class="community valign-text-middle taviraj-medium-lemon-14px">
                                      {{ community }}
                                    </div>
                                  </div>
                                </div>
                                <div class="container-573">
                                  <component105
                                    :symbol="component105Props.symbol"
                                    :twitter="component105Props.twitter"
                                  />
                                  <component106
                                    :facebook="component106Props.facebook"
                                    :container9Props="component106Props.container9Props"
                                  />
                                  <component107 :children="component107Props.children" />
                                </div>
                              </div>
                              <div class="horizontal-border-1">
                                <div class="margin-33">
                                  <div class="container-572">
                                    <div class="search-on valign-text-middle taviraj-semi-bold-lemon-14px">
                                      {{ searchOn }}
                                    </div>
                                  </div>
                                </div>
                                <div class="container-575">
                                  <component108
                                    :twitter="component108Props.twitter"
                                    :component16Props="component108Props.component16Props"
                                  />
                                </div>
                              </div>
                              <div class="horizontal-border">
                                <div class="margin-33">
                                  <div class="container-572">
                                    <div class="source-code valign-text-middle taviraj-medium-lemon-14px">
                                      {{ sourceCode }}
                                    </div>
                                  </div>
                                </div>
                                <div class="container-575">
                                  <component109
                                    :github="component109Props.github"
                                    :container9Props="component109Props.container9Props"
                                  />
                                </div>
                              </div>
                              <div class="horizontal-border">
                                <div class="margin-33">
                                  <div class="container-572">
                                    <div class="api-id valign-text-middle taviraj-medium-lemon-14px">{{ apiId }}</div>
                                  </div>
                                </div>
                                <div class="container-575"><component114 :text="component114Props.text" /></div>
                              </div>
                              <div class="horizontal-border">
                                <div class="margin-33">
                                  <div class="container-572">
                                    <div class="chains valign-text-middle taviraj-semi-bold-lemon-14px">
                                      {{ chains }}
                                    </div>
                                  </div>
                                </div>
                                <div class="container-615">
                                  <component1010 :children="component1010Props.children" />
                                </div>
                              </div>
                              <div class="border-41">
                                <div class="margin-33">
                                  <div class="container-572">
                                    <div class="categories-5 valign-text-middle taviraj-medium-lemon-14px">
                                      {{ categories }}
                                    </div>
                                  </div>
                                </div>
                                <div class="container-616">
                                  <div class="container-617">
                                    <component1011 :children="component1011Props.children" />
                                    <div class="container-618">
                                      <div class="container-619">
                                        <component322 :container8Props="component322Props.container8Props" />
                                      </div>
                                    </div>
                                  </div>
                                </div>
                              </div>
                            </div>
                          </div>
                          <img
                            class="line-29"
                            src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/67751e82be6ae96930ecd4ea/img/line-3.svg"
                            alt="Line 4"
                          />
                          <div class="vertical-border-item">
                            <div class="container-620">
                              <div class="container-569">
                                <div class="heading-2-2">
                                  <div class="btc-converter valign-text-middle">{{ btcConverter }}</div>
                                </div>
                              </div>
                              <div class="container-621">
                                <div class="container-576">
                                  <div class="background-shadow-26">
                                    <div class="input-22">
                                      <div class="container-622">
                                        <div class="number-61 valign-text-middle">{{ number7 }}</div>
                                      </div>
                                    </div>
                                    <div class="container-623">
                                      <div class="btc-20 valign-text-middle taviraj-semi-bold-white-16px">
                                        {{ btc }}
                                      </div>
                                    </div>
                                  </div>
                                </div>
                                <div class="container-576">
                                  <div class="background-shadow-27">
                                    <div class="input-22">
                                      <div class="container-624">
                                        <div class="text-344 valign-text-middle taviraj-semi-bold-white-lilac-16px">
                                          {{ text344 }}
                                        </div>
                                      </div>
                                    </div>
                                    <div class="container-625">
                                      <div class="container-626">
                                        <div class="price-64 valign-text-middle taviraj-semi-bold-white-16px">
                                          {{ price }}
                                        </div>
                                      </div>
                                    </div>
                                  </div>
                                </div>
                              </div>
                            </div>
                          </div>
                          <div class="container-627">
                            <div class="container-577">
                              <div class="container-628">
                                <heading2 :children="heading21Props.children" />
                                <div class="table-body-1">
                                  <div class="row-16">
                                    <div class="cell-95">
                                      <div class="x24h-range-1 valign-text-middle taviraj-semi-bold-lemon-16px">
                                        {{ x24HRange2 }}
                                      </div>
                                    </div>
                                    <div class="data-972">
                                      <p class="text-345 valign-text-middle taviraj-semi-bold-white-14px">
                                        {{ text345 }}
                                      </p>
                                    </div>
                                  </div>
                                  <div class="row-17">
                                    <div class="cell-95">
                                      <div class="x7d-range valign-text-middle taviraj-semi-bold-lemon-16px">
                                        {{ x7DRange }}
                                      </div>
                                    </div>
                                    <div class="data-972">
                                      <div class="text-346 valign-text-middle taviraj-semi-bold-white-14px">
                                        {{ text346 }}
                                      </div>
                                    </div>
                                  </div>
                                  <div class="table-body-item">
                                    <div class="cell-96">
                                      <div class="all-time-high valign-text-middle taviraj-semi-bold-lemon-16px">
                                        {{ allTimeHigh }}
                                      </div>
                                    </div>
                                    <div class="data-973">
                                      <div class="container-578">
                                        <div class="text-347 valign-text-middle taviraj-semi-bold-white-14px">
                                          {{ text347 }}
                                        </div>
                                        <container222 :className="container2225Props.className" />
                                        <div class="percent-82 valign-text-middle wwwcoingeckocomintersemi-bold-14">
                                          {{ percent6 }}
                                        </div>
                                      </div>
                                      <div class="container-579">
                                        <p class="mar-14-2024-7-months valign-text-middle taviraj-normal-lemon-12px">
                                          {{ mar1420247Months }}
                                        </p>
                                      </div>
                                    </div>
                                  </div>
                                  <div class="table-body-item">
                                    <div class="cell-96">
                                      <div class="all-time-low valign-text-middle taviraj-semi-bold-lemon-16px">
                                        {{ allTimeLow }}
                                      </div>
                                    </div>
                                    <div class="data-973">
                                      <div class="container-578">
                                        <div class="text-348 valign-text-middle taviraj-semi-bold-white-14px">
                                          {{ text348 }}
                                        </div>
                                        <container222 :className="container2226Props.className" />
                                        <div
                                          class="percent-83 valign-text-middle taviraj-semi-bold-screamin-green-14px"
                                        >
                                          {{ percent7 }}
                                        </div>
                                      </div>
                                      <div class="container-579">
                                        <p
                                          class="jul-06-2013-over-11-years valign-text-middle taviraj-normal-lemon-12px"
                                        >
                                          {{ jul062013Over11Years }}
                                        </p>
                                      </div>
                                    </div>
                                  </div>
                                </div>
                                <container7 />
                              </div>
                            </div>
                            <div class="container-629">
                              <heading2 :children="heading22Props.children" />
                              <div class="container-630">
                                <p class="the-community-is-bul valign-text-middle">{{ theCommunityIsBul }}</p>
                              </div>
                              <div class="container-631">
                                <component33 :percent="component33Props.percent" />
                                <component34 :percent="component34Props.percent" />
                              </div>
                            </div>
                          </div>
                        </div>
                        <img
                          class="rupee-390"
                          src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/67751e82be6ae96930ecd4ea/img/rupee-1.svg"
                          alt="Rupee"
                        />
                        <img
                          class="rupee-391"
                          src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/67751e82be6ae96930ecd4ea/img/rupee-1.svg"
                          alt="Rupee"
                        />
                        <img
                          class="rupee-392"
                          src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/67751e82be6ae96930ecd4ea/img/rupee-1.svg"
                          alt="Rupee"
                        />
                        <img
                          class="rupee-393"
                          src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/67751e82be6ae96930ecd4ea/img/rupee-1.svg"
                          alt="Rupee"
                        />
                        <img
                          class="rupee-394"
                          src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/67751e82be6ae96930ecd4ea/img/rupee-1.svg"
                          alt="Rupee"
                        />
                        <img
                          class="rupee-395"
                          src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/67751e82be6ae96930ecd4ea/img/rupee-1.svg"
                          alt="Rupee"
                        />
                        <img
                          class="rupee-396"
                          src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/67751e82be6ae96930ecd4ea/img/rupee-1.svg"
                          alt="Rupee"
                        />
                      </div>
                      <img
                        class="rupee-397"
                        src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/67751e82be6ae96930ecd4ea/img/rupee-1.svg"
                        alt="Rupee"
                      />
                    </div>
                    <div class="container-632">
                      <div class="nav">
                        <div class="component-1-7">
                          <div class="text-78 valign-text-middle taviraj-semi-bold-white-16px">{{ text5 }}</div>
                        </div>
                      </div>
                      <div class="container-577">
                        <div class="container-633">
                          <div class="container-634">
                            <div class="heading-2-3">
                              <div class="bitcoin-13 valign-text-middle taviraj-semi-bold-lemon-20px">
                                {{ aboutBitcoinBtc }}
                              </div>
                            </div>
                            <container10 :children="container101Props.children" />
                            <heading3 :children="heading31Props.children" />
                            <container10 :children="container102Props.children" />
                            <heading3 :children="heading32Props.children" />
                            <container10 :children="container103Props.children" />
                            <container11 :children="container111Props.children" />
                            <container11 :children="container112Props.children" />
                            <container11
                              :children="container113Props.children"
                              :className="container113Props.className"
                            />
                            <div class="heading-3-4">
                              <div class="bitcoin-13 valign-text-middle taviraj-semi-bold-lemon-20px">
                                {{ bitcoinMining }}
                              </div>
                            </div>
                            <container10 :children="container104Props.children" />
                            <container11 :children="container114Props.children" />
                            <container11 :children="container115Props.children" />
                            <div class="container-635">
                              <p class="to-learn-more-about valign-text-middle taviraj-medium-white-14px">
                                {{ toLearnMoreAbout }}
                              </p>
                            </div>
                            <div class="list">
                              <div class="item"><component1 :children="component11Props.children" /></div>
                              <div class="item-1"><component1 :children="component12Props.children" /></div>
                            </div>
                            <div class="heading-3-5">
                              <p class="how-to-keep-your-bitcoin-safe valign-text-middle">
                                {{ howToKeepYourBitcoinSafe }}
                              </p>
                            </div>
                            <div class="container-636">
                              <p class="whentransacting-coi valign-text-middle">{{ whentransactingCoi }}</p>
                            </div>
                          </div>
                        </div>
                        <div class="container-637">
                          <div class="component-3-42">
                            <div class="container-570">
                              <div class="read-more valign-text-middle taviraj-semi-bold-white-14px">
                                {{ readMore }}
                              </div>
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                    <div class="make-a-ad-image" :style="{ 'background-image': 'url(' + makeAAdImage + ')' }"></div>
                  </div>
                </div>
              </div>
            </div>
            <div class="overlap-group6-13">
              <img
                class="social-icons-168"
                src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/677504417b0079982c5b5748/img/social-icons-3.svg"
                alt="Social Icons"
              />
              <img
                class="line-114-23"
                src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/677504417b0079982c5b5748/img/line-114.svg"
                alt="Line 114"
              />
              <div class="frame-14399">
                <div class="frame-14398"></div>
                <div class="rectangle-5227-21"></div>
                <img
                  class="social-icons-169"
                  src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/67751f0f11607350f17e4ccd/img/social-icons-1.svg"
                  alt="Social Icons"
                />
                <img
                  class="social-icons-170"
                  src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/67751f0f11607350f17e4ccd/img/social-icons-6.svg"
                  alt="Social Icons"
                />
                <img
                  class="social-icons-171"
                  src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/6775168f11607350f17e4cb9/img/social-icons-1.svg"
                  alt="Social Icons"
                />
                <img
                  class="social-icons-172"
                  src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/67751f0f11607350f17e4ccd/img/social-icons-3.svg"
                  alt="Social Icons"
                />
                <img
                  class="social-icons-173"
                  src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/6775168f11607350f17e4cb9/img/social-icons-4.svg"
                  alt="Social Icons"
                />
                <img
                  class="social-icons-174"
                  src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/67751f0f11607350f17e4ccd/img/social-icons-5.svg"
                  alt="Social Icons"
                />
                <img
                  class="social-icons-175"
                  src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/67751f0f11607350f17e4ccd/img/social-icons-7.svg"
                  alt="Social Icons"
                />
                <div class="follow-us-21 valign-text-middle taviraj-semi-bold-lemon-18px">{{ followUs }}</div>
                <div class="email-22 valign-text-middle taviraj-semi-bold-lemon-18px">{{ email }}</div>
                <div class="abc123gmailcom-21 valign-text-middle taviraj-semi-bold-white-13px">
                  {{ abc123GmailCom }}
                </div>
                <div class="about-us-21 valign-text-middle taviraj-semi-bold-lemon-18px">{{ aboutUs }}</div>
                <div class="company-name-and-symbol-21 valign-text-middle taviraj-semi-bold-white-18px">
                  {{ companyNameAndSymbol }}
                </div>
                <div class="privacy-policy-21 valign-text-middle taviraj-semi-bold-lemon-18px">{{ privacyPolicy }}</div>
                <div class="terms-of-use-21 valign-text-middle taviraj-semi-bold-lemon-18px">{{ termsOfUse }}</div>
                <p class="all-content-on-abcc-21 taviraj-medium-white-13px">{{ allContentOnAbcC }}</p>
              </div>
              <x-footer
                :className="xFooterProps.className"
                :container4Props="xFooterProps.container4Props"
                :container7Props2="xFooterProps.container7Props2"
                :container7Props22="xFooterProps.container7Props22"
                :container7Props23="xFooterProps.container7Props23"
              />
            </div>
          </div>
          <div class="rectangle-5218-19"></div>
        </div>
      </div>
      <div class="rectangle-5217-19"></div>
    </div>
  </div>
</template>

<script>
import Component5 from "./Component5";
import Navbar from "./Navbar";
import Avatar from "./Avatar";
import Container62 from "./Container62";
import Component15 from "./Component15";
import Container2 from "./Container2";
import Margin from "./Margin";
import Component8 from "./Component8";
import Component82 from "./Component82";
import Component83 from "./Component83";
import Component84 from "./Component84";
import Component85 from "./Component85";
import Component86 from "./Component86";
import Component87 from "./Component87";
import Component88 from "./Component88";
import Component89 from "./Component89";
import Component810 from "./Component810";
import Component9 from "./Component9";
import Component92 from "./Component92";
import Cell42 from "./Cell42";
import xData from "./xData";
import Container222 from "./Container222";
import Container5 from "./Container5";
import Data252 from "./Data252";
import Container6 from "./Container6";
import Data332 from "./Data332";
import Container7 from "./Container7";
import Component10 from "./Component10";
import Component102 from "./Component102";
import Component103 from "./Component103";
import Component3 from "./Component3";
import Component104 from "./Component104";
import Component105 from "./Component105";
import Component106 from "./Component106";
import Component107 from "./Component107";
import Component108 from "./Component108";
import Component109 from "./Component109";
import Component114 from "./Component114";
import Component1010 from "./Component1010";
import Component1011 from "./Component1011";
import Component322 from "./Component322";
import Heading2 from "./Heading2";
import Component33 from "./Component33";
import Component34 from "./Component34";
import Container10 from "./Container10";
import Heading3 from "./Heading3";
import Container11 from "./Container11";
import Component1 from "./Component1";
import xFooter from "./xFooter";
export default {
  name: "MacBookPro1435",
  components: {
    Component5,
    Navbar,
    Avatar,
    Container62,
    Component15,
    Container2,
    Margin,
    Component8,
    Component82,
    Component83,
    Component84,
    Component85,
    Component86,
    Component87,
    Component88,
    Component89,
    Component810,
    Component9,
    Component92,
    Cell42,
    xData,
    Container222,
    Container5,
    Data252,
    Container6,
    Data332,
    Container7,
    Component10,
    Component102,
    Component103,
    Component3,
    Component104,
    Component105,
    Component106,
    Component107,
    Component108,
    Component109,
    Component114,
    Component1010,
    Component1011,
    Component322,
    Heading2,
    Component33,
    Component34,
    Container10,
    Heading3,
    Container11,
    Component1,
    xFooter,
  },
  props: [
    "place1",
    "place2",
    "bitcoinPng1",
    "title",
    "text1",
    "bitcoinPng2",
    "bitcoin",
    "text326",
    "percent1",
    "x24HRange1",
    "addToPortfolio",
    "buySell",
    "wallet",
    "group1",
    "group2",
    "group3",
    "group4",
    "group5",
    "group6",
    "group7",
    "group8",
    "group9",
    "text2",
    "text3",
    "text4",
    "text330",
    "text331",
    "text327",
    "text332",
    "text333",
    "text328",
    "text334",
    "text335",
    "x20Oct",
    "text336",
    "text329",
    "text337",
    "number1",
    "number2",
    "number3",
    "number4",
    "number5",
    "number6",
    "group10",
    "x8100Lakh",
    "x8000Lakh",
    "x8025Lakh",
    "x8050Lakh",
    "x8125Lakh",
    "vector2",
    "vector3",
    "x8075Lakh",
    "x24H",
    "x14D",
    "x30D",
    "x1Yr",
    "percent2",
    "percent3",
    "percent4",
    "percent5",
    "marketCap",
    "fullyDilutedValuation",
    "address",
    "text340",
    "circulatingSupply",
    "text341",
    "totalSupply",
    "name",
    "info",
    "website",
    "explorers",
    "wallets",
    "community",
    "searchOn",
    "sourceCode",
    "apiId",
    "chains",
    "categories",
    "btcConverter",
    "number7",
    "btc",
    "text344",
    "price",
    "x24HRange2",
    "text345",
    "x7DRange",
    "text346",
    "allTimeHigh",
    "text347",
    "percent6",
    "mar1420247Months",
    "allTimeLow",
    "text348",
    "percent7",
    "jul062013Over11Years",
    "theCommunityIsBul",
    "text5",
    "aboutBitcoinBtc",
    "bitcoinMining",
    "toLearnMoreAbout",
    "howToKeepYourBitcoinSafe",
    "whentransactingCoi",
    "readMore",
    "makeAAdImage",
    "followUs",
    "email",
    "abc123GmailCom",
    "aboutUs",
    "companyNameAndSymbol",
    "privacyPolicy",
    "termsOfUse",
    "allContentOnAbcC",
    "avatarProps",
    "container621Props",
    "container622Props",
    "component151Props",
    "component152Props",
    "container2Props",
    "margin1Props",
    "margin2Props",
    "component8Props",
    "component82Props",
    "component83Props",
    "component84Props",
    "component85Props",
    "component861Props",
    "component871Props",
    "component872Props",
    "component862Props",
    "component88Props",
    "component89Props",
    "component810Props",
    "component9Props",
    "cell421Props",
    "cell422Props",
    "xData1Props",
    "container2221Props",
    "xData2Props",
    "container2222Props",
    "container2223Props",
    "container2224Props",
    "data2521Props",
    "container61Props",
    "data2522Props",
    "container62Props",
    "container63Props",
    "container64Props",
    "container5Props",
    "component10Props",
    "component102Props",
    "component103Props",
    "component31Props",
    "component104Props",
    "component32Props",
    "component105Props",
    "component106Props",
    "component107Props",
    "component108Props",
    "component109Props",
    "component114Props",
    "component1010Props",
    "component1011Props",
    "component322Props",
    "heading21Props",
    "container2225Props",
    "container2226Props",
    "heading22Props",
    "component33Props",
    "component34Props",
    "container101Props",
    "heading31Props",
    "container102Props",
    "heading32Props",
    "container103Props",
    "container111Props",
    "container112Props",
    "container113Props",
    "container104Props",
    "container114Props",
    "container115Props",
    "component11Props",
    "component12Props",
    "xFooterProps",
  ],
};
</script>

<style>
.macbook-pro-14u34-35 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  gap: 32px;
  height: 3363px;
  overflow: hidden;
  width: 1512px;
}

.flex-col-33 {
  align-items: flex-end;
  display: flex;
  flex-direction: column;
  gap: 13px;
  margin-left: -5px;
  margin-top: 17px;
  min-height: 3530px;
  width: 1512px;
}

.frame-14335-20 {
  align-items: center;
  display: flex;
  gap: 40px;
  padding: 16px 0px 20px 100px;
  position: relative;
  width: 1512px;
}

.place-79 {
  height: 51px;
  letter-spacing: 0;
  line-height: normal;
  margin-top: -1px;
  position: relative;
  width: 120px;
}

.bedtime-15 {
  height: 50px;
  position: relative;
  width: 49.02px;
}

.flex-row-47 {
  align-items: flex-start;
  display: flex;
  gap: 41px;
  height: 3430px;
  margin-right: 3px;
  min-width: 1449px;
}

.flex-col-34 {
  align-items: center;
  display: flex;
  flex-direction: column;
  min-height: 3430px;
  width: 1402px;
}

.line-7-1 {
  height: 1px;
  margin-left: 6px;
  object-fit: cover;
  width: 1388px;
}

.frame-14331-14 {
  align-items: center;
  display: flex;
  flex-direction: column;
  gap: 46px;
  margin-top: 37px;
  position: relative;
  width: 1266px;
}

.frame-14329-11 {
  align-self: stretch;
  background-image: url(https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/67751f0f11607350f17e4ccd/img/frame-14329.svg);
  background-position: 50% 50%;
  background-size: cover;
  height: 118px;
  position: relative;
  width: 100%;
}

.container-580 {
  align-items: center;
  align-self: stretch;
  background-color: var(--black);
  border-bottom-style: solid;
  border-bottom-width: 1px;
  border-color: var(--dhancowhite);
  display: flex;
  flex: 0 0 auto;
  gap: 334px;
  padding: 25px 7px;
  position: relative;
  width: 100%;
}

.component-3-39 {
  align-items: center;
  background-color: var(--ebony);
  border: 1px solid;
  border-color: var(--mischka);
  border-radius: 8px;
  cursor: pointer;
  display: flex;
  gap: 112px;
  justify-content: center;
  padding: 6px 10px;
  position: relative;
  width: 70px;
}

.container-581 {
  align-items: center;
  display: flex;
  flex-direction: column;
  position: relative;
  width: 30px;
}

.place-80 {
  letter-spacing: 0;
  line-height: 16px;
  margin-left: -5px;
  margin-right: -5px;
  margin-top: -1px;
  position: relative;
  text-align: center;
  white-space: nowrap;
  width: fit-content;
}

.group-5 {
  height: 55px;
  position: relative;
  width: 218px;
}

.bitcoinpng-10 {
  background-position: 50% 50%;
  background-size: cover;
  border-radius: 9999px;
  height: 55px;
  left: 0;
  position: absolute;
  top: 0;
  width: 55px;
}

.heading-1-9 {
  align-items: center;
  display: inline-flex;
  flex-wrap: wrap;
  gap: 0px 4px;
  left: 63px;
  position: absolute;
  top: 14px;
}

.container-582,
.main,
.container-587,
.container-589,
.container-618,
.heading-2-2 {
  align-items: flex-start;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  position: relative;
}

.title-16,
.bitcoin-14,
.info {
  letter-spacing: 0;
  line-height: 28px;
  margin-top: -1px;
  position: relative;
  white-space: nowrap;
  width: fit-content;
}

.container-583 {
  align-items: flex-start;
  background-color: var(--white-4);
  border: 1px solid;
  border-color: #ffffff40;
  border-radius: 10px;
  display: flex;
  height: 39px;
  margin-right: -4px;
  padding: 0px 30px 0px 20px;
  position: relative;
  width: 300px;
}

.component-15-1 {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex-direction: column;
  margin-right: -7px;
  position: relative;
  width: 257px;
}

.frame-14364 {
  align-items: center;
  display: flex;
  flex: 0 0 auto;
  gap: 10px;
  justify-content: center;
  margin-bottom: -1px;
  margin-right: -34px;
  padding: 12px 0px;
  position: relative;
  width: 291px;
}

.text-74 {
  flex: 1;
  letter-spacing: 0;
  line-height: 16px;
  margin-top: -1px;
  position: relative;
}

.container-584 {
  height: 2101px;
  position: relative;
  width: 1266px;
}

.vertical-border {
  align-items: flex-start;
  border-color: var(--ebony);
  border-right-style: solid;
  border-right-width: 1px;
  display: flex;
  flex-direction: column;
  height: 44px;
  left: 0;
  padding: 0px 25px 0px 0px;
  position: absolute;
  top: 0;
  width: 419px;
}

.nav-breadcrumbs {
  align-self: stretch;
  flex: 0 0 auto;
  position: relative;
  width: 100%;
}

.overlap-group4-12 {
  height: 2057px;
  left: 0;
  position: absolute;
  top: 44px;
  width: 1266px;
}

.overlap-group5-12 {
  height: 1729px;
  left: 0;
  position: absolute;
  top: 0;
  width: 1266px;
}

.overlap-group3-19 {
  height: 759px;
  left: 1px;
  position: absolute;
  top: 0;
  width: 1265px;
}

.vertical-border-1 {
  align-items: flex-start;
  border-color: var(--ebony);
  border-right-style: solid;
  border-right-width: 1px;
  display: flex;
  flex-direction: column;
  height: 175px;
  left: 10px;
  padding: 0px 25px 0px 0px;
  position: absolute;
  top: 30px;
  width: 419px;
}

.container-585 {
  align-items: flex-start;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  margin-bottom: -33px;
  margin-right: -25px;
  position: relative;
  width: 419px;
}

.container-586 {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex-direction: column;
  gap: 18px;
  height: 166px;
  position: relative;
  width: 100%;
}

.container-569 {
  align-items: center;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  gap: 8px;
  position: relative;
  width: 100%;
}

.bitcoinpng-11 {
  background-position: 50% 50%;
  background-size: cover;
  border-radius: 9999px;
  height: 33px;
  max-width: 398.33px;
  position: relative;
  width: 33px;
}

.heading-1-10 {
  align-items: center;
  display: inline-flex;
  flex: 0 0 auto;
  flex-wrap: wrap;
  gap: 0px 4px;
  position: relative;
}

.container-588 {
  align-items: center;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  position: relative;
  width: 100%;
}

.text-326 {
  letter-spacing: 0;
  line-height: 40px;
  margin-top: -1px;
  position: relative;
  white-space: nowrap;
  width: fit-content;
}

.container-590 {
  align-items: center;
  display: inline-flex;
  flex: 0 0 auto;
  gap: 6.25px;
  padding: 0px 0px 0px 6.25px;
  position: relative;
}

.percent-77 {
  color: var(--screamin-green);
  font-family: var(--font-family-inter);
  font-size: var(--font-size-xxxxl);
  font-weight: 700;
  letter-spacing: 0;
  line-height: 28px;
  margin-top: -1px;
  position: relative;
  white-space: nowrap;
  width: fit-content;
}

.container-591 {
  align-items: flex-start;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  padding: 3px 0px 2.52px 8px;
  position: relative;
}

.container-592 {
  align-items: flex-start;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  gap: 8px;
  max-width: 400px;
  position: relative;
  width: 100%;
}

.background {
  align-items: flex-start;
  align-self: stretch;
  background-color: var(--ebony);
  border-radius: 9999px;
  display: flex;
  height: 6px;
  position: relative;
  width: 100%;
}

.gradient {
  background: linear-gradient(180deg, rgb(255, 221, 51) 0%, rgb(0, 168, 62) 100%);
  border-radius: 4px;
  height: 6px;
  position: relative;
  width: 400px;
}

.container-593 {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  justify-content: space-between;
  position: relative;
  width: 100%;
}

.x24h-range {
  letter-spacing: 0;
  line-height: 16px;
  margin-top: -1px;
  position: relative;
  white-space: nowrap;
  width: fit-content;
}

.frame-14355 {
  align-items: center;
  display: inline-flex;
  flex: 0 0 auto;
  gap: 10px;
  justify-content: center;
  position: relative;
}

.margin-34 {
  align-items: flex-start;
  display: flex;
  flex-direction: column;
  padding: 0px 0px 8px;
  position: relative;
  width: 153px;
}

.component-7-17 {
  align-items: center;
  align-self: stretch;
  border: 1px solid;
  border-color: var(--mischka);
  border-radius: 8px;
  display: flex;
  flex: 0 0 auto;
  padding: 8px 12px 6px;
  position: relative;
  width: 100%;
}

.container-594 {
  align-items: center;
  display: inline-flex;
  flex: 0 0 auto;
  gap: 0.9px;
  justify-content: center;
  margin-right: -6.53px;
  padding: 0px 2.84e-14px 0px 0.88px;
  position: relative;
}

.add-to-portfolio {
  letter-spacing: 0;
  line-height: 20px;
  margin-top: -1px;
  position: relative;
  text-align: center;
  white-space: nowrap;
  width: fit-content;
}

.container-595 {
  align-items: center;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  height: 42px;
  position: relative;
}

.container-596 {
  align-items: flex-start;
  display: inline-flex;
  height: 37px;
  justify-content: center;
  position: relative;
}

.container-597 {
  align-items: flex-start;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  margin-bottom: -1px;
  padding: 0px 0px 4px;
  position: relative;
}

.component-3-40 {
  align-items: center;
  background-color: var(--candlelight-2);
  border-radius: 8px;
  display: inline-flex;
  height: 34px;
  justify-content: center;
  padding: 6px 10px;
  position: relative;
}

.container-570 {
  align-items: center;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  position: relative;
}

.buy-sell,
.wallet,
.read-more {
  letter-spacing: 0;
  line-height: 16px;
  margin-top: -1px;
  position: relative;
  text-align: center;
  white-space: nowrap;
  width: fit-content;
}

.container-598 {
  align-items: flex-start;
  align-self: stretch;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  position: relative;
}

.container-599 {
  align-items: flex-start;
  display: inline-flex;
  flex: 0 0 auto;
  justify-content: center;
  position: relative;
}

.container-600 {
  align-items: flex-start;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  padding: 0px 0px 4px;
  position: relative;
}

.component-3-41 {
  align-items: center;
  background-color: var(--candlelight-2);
  border-radius: 8px;
  display: inline-flex;
  gap: 0.01px;
  height: 34px;
  justify-content: center;
  padding: 6px 10px;
  position: relative;
}

.container-601 {
  align-items: flex-start;
  display: flex;
  flex-direction: column;
  height: 759px;
  left: 422px;
  padding: 0px 0px 0px 24px;
  position: absolute;
  top: 0;
  width: 843px;
}

.margin-35 {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  padding: 8px 0px 16px;
  position: relative;
  width: 100%;
}

.container-602 {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  gap: 8px;
  position: relative;
  width: 100%;
}

.container-603 {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  gap: 6px;
  position: relative;
  width: 100%;
}

.container-604 {
  align-items: flex-start;
  align-self: stretch;
  display: inline-flex;
  flex: 0 0 auto;
  flex-wrap: wrap;
  gap: 0px 4px;
  position: relative;
}

.group-1 {
  align-items: flex-start;
  align-self: stretch;
  background-color: var(--black);
  border: 1px solid;
  border-color: var(--mischka);
  border-radius: 8px;
  display: inline-flex;
  flex: 0 0 auto;
  gap: 3.6px;
  padding: 4px;
  position: relative;
}

.group-2 {
  align-items: flex-start;
  align-self: stretch;
  background-color: var(--black);
  border: 1px solid;
  border-color: var(--mischka);
  border-radius: 8px;
  display: inline-flex;
  flex: 0 0 auto;
  gap: 3.65px;
  padding: 4px;
  position: relative;
}

.container-605::-webkit-scrollbar,
.container-622::-webkit-scrollbar,
.container-624::-webkit-scrollbar,
.nav::-webkit-scrollbar {
  display: none;
  width: 0;
}

.container-605 {
  align-items: flex-start;
  align-self: stretch;
  border: 1px solid;
  border-color: var(--mischka);
  border-radius: 8px;
  display: flex;
  flex-direction: column;
  overflow: scroll;
  position: relative;
  width: 431px;
}

.group-3 {
  align-items: flex-start;
  background-color: var(--black);
  border-radius: 8px;
  display: flex;
  flex: 0 0 auto;
  gap: 3.6px;
  padding: 4px;
  position: relative;
  width: 446px;
}

.container-606 {
  align-items: flex-start;
  border: 1px solid;
  border-color: var(--dhancowhite);
  display: flex;
  flex-direction: column;
  gap: 8px;
  height: 600px;
  margin-right: -47px;
  position: relative;
  width: 866px;
}

.container-607 {
  align-items: flex-start;
  display: flex;
  flex-direction: column;
  height: 595px;
  justify-content: center;
  position: relative;
  width: 858px;
}

.container-608 {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 1;
  flex-direction: column;
  flex-grow: 1;
  overflow: hidden;
  position: relative;
  width: 100%;
}

.component-4-46 {
  height: 600px;
  position: relative;
  width: 820px;
}

.overlap-group-85 {
  height: 599px;
  left: 1px;
  position: absolute;
  top: 1px;
  width: 858px;
}

.vector-40 {
  height: 594px;
  left: 0;
  position: absolute;
  top: 0;
  width: 830px;
}

.group-4 {
  height: 448px;
  left: 20px;
  position: absolute;
  top: 49px;
  width: 683px;
}

.group-6 {
  height: 40px;
  left: 52px;
  position: absolute;
  top: 544px;
  width: 654px;
}

.group-8 {
  height: 360px;
  left: 9px;
  position: absolute;
  top: 48px;
  width: 748px;
}

.group {
  height: 1px;
  left: 9px;
  position: absolute;
  top: 584px;
  width: 748px;
}

.group-11 {
  height: 10px;
  left: 9px;
  position: absolute;
  top: 497px;
  width: 748px;
}

.group-14 {
  height: 358px;
  left: 757px;
  position: absolute;
  top: 49px;
  width: 1px;
}

.group-15 {
  height: 40px;
  left: 9px;
  position: absolute;
  top: 544px;
  width: 1px;
}

.group-16 {
  height: 535px;
  left: 9px;
  position: absolute;
  top: 49px;
  width: 748px;
}

.text-75 {
  color: #1e293b;
  font-family: var(--font-family-inter);
  font-size: var(--font-size-xxxl);
  font-weight: 400;
  left: 409px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  text-align: center;
  top: 4px;
}

.text-76 {
  color: #666666;
  font-family: var(--font-family-inter);
  font-size: var(--font-size-s);
  font-weight: 400;
  left: 409px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  text-align: center;
  top: 10px;
}

.text-77 {
  color: var(--black);
  font-family: var(--font-family-inter);
  font-size: var(--font-size-s);
  font-weight: 400;
  left: 9px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  top: 583px;
}

.group-17 {
  align-items: flex-start;
  display: flex;
  height: 14px;
  left: 8px;
  min-width: 736px;
  position: absolute;
  top: 504px;
}

.text-330 {
  letter-spacing: 0;
  line-height: normal;
  min-height: 14px;
  text-align: center;
  width: 33px;
}

.text-331 {
  letter-spacing: 0;
  line-height: normal;
  margin-left: 27px;
  min-height: 14px;
  text-align: center;
  width: 31px;
}

.text-3-1 {
  letter-spacing: 0;
  line-height: normal;
  margin-left: 31px;
  min-height: 14px;
  text-align: center;
  width: 31px;
}

.text-332 {
  letter-spacing: 0;
  line-height: normal;
  margin-left: 29px;
  min-height: 14px;
  text-align: center;
  width: 31px;
}

.text-328 {
  letter-spacing: 0;
  line-height: normal;
  margin-left: 32px;
  min-height: 14px;
  text-align: center;
  width: 31px;
}

.text-334 {
  letter-spacing: 0;
  line-height: normal;
  margin-left: 31px;
  min-height: 14px;
  text-align: center;
  width: 33px;
}

.text-3-2 {
  letter-spacing: 0;
  line-height: normal;
  margin-left: 29px;
  min-height: 14px;
  text-align: center;
  width: 33px;
}

.x20-oct {
  letter-spacing: 0;
  line-height: normal;
  margin-left: 25px;
  min-height: 14px;
  text-align: center;
  width: 41px;
}

.text-336 {
  letter-spacing: 0;
  line-height: normal;
  margin-left: 26px;
  min-height: 14px;
  text-align: center;
  width: 33px;
}

.group-18 {
  align-items: flex-start;
  display: flex;
  gap: 103px;
  height: 20px;
  left: 56px;
  min-width: 693px;
  position: absolute;
  top: 568px;
}

.number-60 {
  letter-spacing: 0;
  line-height: normal;
  min-height: 20px;
  width: 28px;
}

.group-19 {
  height: 40px;
  left: 9px;
  position: absolute;
  top: 544px;
  width: 773px;
}

.rupee-382 {
  height: 14px;
  left: 768px;
  position: absolute;
  top: 397px;
  width: 9px;
}

.rupee-383 {
  height: 14px;
  left: 768px;
  position: absolute;
  top: 323px;
  width: 9px;
}

.rupee-384 {
  height: 14px;
  left: 766px;
  position: absolute;
  top: 253px;
  width: 9px;
}

.rupee-385 {
  height: 14px;
  left: 766px;
  position: absolute;
  top: 115px;
  width: 9px;
}

.rupee-386 {
  height: 14px;
  left: 765px;
  position: absolute;
  top: 42px;
  width: 9px;
}

.x8100-lakh {
  height: 17px;
  left: 776px;
  letter-spacing: 0;
  line-height: 16.7px;
  position: absolute;
  top: 112px;
  white-space: nowrap;
  width: 82px;
}

.x8000-lakh {
  height: 17px;
  left: 779px;
  letter-spacing: 0;
  line-height: 16.7px;
  position: absolute;
  top: 395px;
  white-space: nowrap;
  width: 79px;
}

.x8025-lakh {
  height: 17px;
  left: 779px;
  letter-spacing: 0;
  line-height: 16.7px;
  position: absolute;
  top: 320px;
  white-space: nowrap;
  width: 77px;
}

.x8050-lakh {
  height: 17px;
  left: 777px;
  letter-spacing: 0;
  line-height: 16.7px;
  position: absolute;
  top: 250px;
  white-space: nowrap;
  width: 81px;
}

.x8125-lakh {
  height: 17px;
  left: 776px;
  letter-spacing: 0;
  line-height: 16.7px;
  position: absolute;
  top: 39px;
  white-space: nowrap;
  width: 77px;
}

.vector-container {
  height: 449px;
  left: -19291px;
  position: absolute;
  top: 3556px;
  width: 749px;
}

.vector-41 {
  height: 448px;
  left: 0;
  position: absolute;
  top: 0;
  width: 748px;
}

.vector-42 {
  height: 449px;
  left: 0;
  position: absolute;
  top: 0;
  width: 749px;
}

.paragraph-192 {
  height: 1px;
  left: 0;
  position: absolute;
  top: 0;
  width: 1px;
}

.x8075-lakh {
  height: 17px;
  left: 778px;
  letter-spacing: 0;
  line-height: 16.7px;
  position: absolute;
  top: 176px;
  white-space: nowrap;
  width: 77px;
}

.rupee-387 {
  height: 14px;
  left: 767px;
  position: absolute;
  top: 179px;
  width: 9px;
}

.margin-36 {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  margin-bottom: -14.52px;
  padding: 0px 0px 24px;
  position: relative;
  width: 100%;
}

.border-40 {
  align-items: flex-start;
  align-self: stretch;
  border: 1px solid;
  border-color: var(--white-2);
  border-radius: 12px;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  padding: 1px;
  position: relative;
  width: 100%;
}

.table-6 {
  align-items: flex-start;
  align-self: stretch;
  border-radius: 12px;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  justify-content: center;
  overflow: hidden;
  position: relative;
  width: 100%;
}

.header-row {
  align-items: center;
  align-self: stretch;
  display: flex;
  height: 40.5px;
  justify-content: center;
  position: relative;
  width: 100%;
}

.cell-97 {
  align-items: flex-start;
  background-color: var(--black);
  border-bottom-style: solid;
  border-bottom-width: 1px;
  border-left-style: solid;
  border-left-width: 1px;
  display: flex;
  flex-direction: column;
  height: 40.5px;
  justify-content: center;
  padding: 11.5px 48.75px 13px 54.74px;
  position: relative;
  width: 126.13px;
}

.x24h-6 {
  letter-spacing: 0;
  line-height: 16px;
  margin-right: -8.36px;
  margin-top: -1px;
  position: relative;
  text-align: center;
  white-space: nowrap;
  width: fit-content;
}

.cell-98 {
  align-items: flex-start;
  background-color: var(--black);
  border-bottom-style: solid;
  border-bottom-width: 1px;
  border-left-style: solid;
  border-left-width: 1px;
  display: flex;
  flex-direction: column;
  height: 40.5px;
  justify-content: center;
  padding: 11.5px 58.93px 13px 64.9px;
  position: relative;
  width: 144.39px;
}

.x14d {
  letter-spacing: 0;
  line-height: 16px;
  margin-right: -9.44px;
  margin-top: -1px;
  position: relative;
  text-align: center;
  white-space: nowrap;
  width: fit-content;
}

.cell-99 {
  align-items: flex-start;
  background-color: var(--black);
  border-bottom-style: solid;
  border-bottom-width: 1px;
  border-left-style: solid;
  border-left-width: 1px;
  display: flex;
  flex-direction: column;
  height: 40.5px;
  justify-content: center;
  padding: 11.5px 50.09px 13px 56.09px;
  position: relative;
  width: 129.23px;
}

.x30d {
  letter-spacing: 0;
  line-height: 16px;
  margin-right: -6.95px;
  margin-top: -1px;
  position: relative;
  text-align: center;
  white-space: nowrap;
  width: fit-content;
}

.cell-100 {
  align-items: flex-start;
  background-color: var(--black);
  border-bottom-style: solid;
  border-bottom-width: 1px;
  border-left-style: solid;
  border-left-width: 1px;
  display: flex;
  flex-direction: column;
  height: 40.5px;
  justify-content: center;
  margin-right: -1.84px;
  padding: 11.5px 69.32px 13px 75.81px;
  position: relative;
  width: 157.36px;
}

.x1yr {
  letter-spacing: 0;
  line-height: 16px;
  margin-right: -15.77px;
  margin-top: -1px;
  position: relative;
  text-align: center;
  white-space: nowrap;
  width: fit-content;
}

.body-row {
  align-items: center;
  align-self: stretch;
  display: flex;
  height: 39.02px;
  justify-content: center;
  position: relative;
  width: 100%;
}

.data-974 {
  align-items: center;
  border-color: var(--black);
  border-left-style: solid;
  border-left-width: 1px;
  display: flex;
  gap: 4.06px;
  height: 39.02px;
  padding: 10.24px 40.67px 10.26px 44.72px;
  position: relative;
  width: 126.13px;
}

.percent-78 {
  letter-spacing: 0;
  line-height: 18.5px;
  margin-right: -6.45px;
  margin-top: -1.24px;
  position: relative;
  text-align: center;
  white-space: nowrap;
  width: fit-content;
}

.data-975 {
  align-items: center;
  border-color: var(--black);
  border-left-style: solid;
  border-left-width: 1px;
  display: flex;
  gap: 4.06px;
  height: 39.02px;
  padding: 10.24px 45.03px 10.26px 49.09px;
  position: relative;
  width: 144.39px;
}

.percent-79 {
  letter-spacing: 0;
  line-height: 18.5px;
  margin-right: -5.91px;
  margin-top: -1.24px;
  position: relative;
  text-align: center;
  white-space: nowrap;
  width: fit-content;
}

.data-976 {
  align-items: center;
  border-color: var(--black);
  border-left-style: solid;
  border-left-width: 1px;
  display: flex;
  gap: 4.05px;
  height: 39.02px;
  padding: 10.24px 41.41px 10.26px 45.47px;
  position: relative;
  width: 129.23px;
}

.percent-80 {
  letter-spacing: 0;
  line-height: 18.5px;
  margin-right: -4.82px;
  margin-top: -1.24px;
  position: relative;
  text-align: center;
  white-space: nowrap;
  width: fit-content;
}

.data-977 {
  align-items: center;
  border-color: var(--black);
  border-left-style: solid;
  border-left-width: 1px;
  display: flex;
  gap: 4.06px;
  height: 39.02px;
  margin-right: -1.84px;
  padding: 10.24px 47.64px 10.26px 52.2px;
  position: relative;
  width: 157.36px;
}

.percent-81 {
  letter-spacing: 0;
  line-height: 18.5px;
  margin-right: -7.67px;
  margin-top: -1.24px;
  position: relative;
  text-align: center;
  white-space: nowrap;
  width: fit-content;
}

.rupee-388 {
  height: 39px;
  left: 0;
  position: absolute;
  top: 84px;
  width: 24px;
}

.rupee-389 {
  height: 15px;
  left: 307px;
  position: absolute;
  top: 153px;
  width: 9px;
}

.overlap-group2-22 {
  height: 1475px;
  left: 0;
  position: absolute;
  top: 254px;
  width: 394px;
}

.vertical-border-2 {
  align-items: flex-start;
  border-color: var(--ebony);
  border-right-style: solid;
  border-right-width: 1px;
  display: flex;
  flex-direction: column;
  gap: 12px;
  left: 0;
  position: absolute;
  top: 0;
  width: 394px;
}

.line-3-2 {
  height: 1px;
  margin-right: -1.67px;
  margin-top: -1px;
  object-fit: cover;
  position: relative;
  width: 396px;
}

.margin-37 {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  padding: 0px 0px 16px;
  position: relative;
  width: 100%;
}

.container-609,
.container-610,
.container-619,
.container-628,
.container-630,
.heading-2-3,
.item {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  position: relative;
  width: 100%;
}

.table-body,
.container-611,
.table-body-1 {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  justify-content: center;
  position: relative;
  width: 100%;
}

.row-10,
.row-16 {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  height: 46px;
  justify-content: space-between;
  padding: 12px 0px;
  position: relative;
  width: 100%;
}

.cell-94 {
  align-items: center;
  align-self: stretch;
  display: inline-flex;
  flex: 0 0 auto;
  padding: 0.5px 1px 1.5px;
  position: relative;
}

.market-cap-7,
.total-supply,
.name-16,
.website,
.explorers,
.wallets,
.community,
.search-on,
.source-code,
.api-id,
.chains,
.categories-5,
.btc-20,
.price-64,
.x24h-range-1,
.x7d-range,
.all-time-high,
.all-time-low,
.text-78 {
  letter-spacing: 0;
  line-height: 20px;
  margin-top: -1px;
  position: relative;
  white-space: nowrap;
  width: fit-content;
}

.container-571 {
  align-items: flex-start;
  display: flex;
  flex: 1;
  flex-grow: 1;
  margin-left: -1.42e-14px;
  padding: 2px 1.75px 1px;
  position: relative;
}

.row-11,
.row-12,
.row-14,
.row-15,
.row-17 {
  align-items: flex-start;
  align-self: stretch;
  border-color: var(--black);
  border-top-style: solid;
  border-top-width: 1px;
  display: flex;
  height: 47px;
  justify-content: space-between;
  padding: 13px 0px 12px;
  position: relative;
  width: 100%;
}

.fully-diluted-valuation {
  color: var(--lemon);
  font-family: var(--font-family-taviraj);
  font-size: var(--font-size-l);
  font-weight: 500;
  letter-spacing: 0;
  line-height: 20px;
  margin-right: -4.5px;
  margin-top: -1px;
  position: relative;
  white-space: nowrap;
  width: fit-content;
}

.address-80 {
  letter-spacing: 0;
  line-height: 20px;
  margin-right: -7.5px;
  margin-top: -1px;
  position: relative;
  white-space: nowrap;
  width: fit-content;
}

.data-972 {
  align-items: flex-end;
  align-self: stretch;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  padding: 1px 1px 1px 8px;
  position: relative;
}

.text-340,
.text-341,
.text-345,
.text-346,
.text-347,
.text-348,
.percent-83 {
  letter-spacing: 0;
  line-height: 20px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.row-13 {
  align-items: flex-start;
  align-self: stretch;
  border-color: var(--black);
  border-top-style: solid;
  border-top-width: 1px;
  display: flex;
  height: 47px;
  justify-content: space-between;
  padding: 13px 0.01px 12px 0px;
  position: relative;
  width: 100%;
}

.circulating-supply {
  letter-spacing: 0;
  line-height: 20px;
  margin-right: -6.5px;
  margin-top: -1px;
  position: relative;
  white-space: nowrap;
  width: fit-content;
}

.data-978 {
  align-items: center;
  align-self: stretch;
  display: inline-flex;
  flex: 0 0 auto;
  gap: 1.76px;
  justify-content: flex-end;
  padding: 0.5px 2.74px 1.5px 8px;
  position: relative;
}

.line-29 {
  height: 1px;
  margin-right: -1.67px;
  object-fit: cover;
  position: relative;
  width: 396px;
}

.vertical-border-item {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  padding: 0px 0px 24px;
  position: relative;
  width: 100%;
}

.container-612 {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  height: 52px;
  justify-content: space-between;
  padding: 12px 0px;
  position: relative;
  width: 100%;
}

.margin-33 {
  align-items: flex-start;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  height: 28px;
  justify-content: center;
  padding: 4px 0px;
  position: relative;
}

.container-572 {
  align-items: flex-start;
  display: inline-flex;
  flex-direction: column;
  height: 20px;
  position: relative;
}

.container-573 {
  align-items: center;
  align-self: stretch;
  display: inline-flex;
  flex: 0 0 auto;
  flex-wrap: wrap;
  gap: 0px 4px;
  justify-content: flex-end;
  padding: 0px 0px 0px 8px;
  position: relative;
}

.horizontal-border {
  align-items: flex-start;
  align-self: stretch;
  border-color: var(--ebony);
  border-top-style: solid;
  border-top-width: 1px;
  display: flex;
  height: 53px;
  justify-content: space-between;
  padding: 13px 0px 12px;
  position: relative;
  width: 100%;
}

.container-574 {
  align-items: flex-start;
  align-self: stretch;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  padding: 0px 0px 0px 8px;
  position: relative;
}

.container-613 {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  position: relative;
  width: 100%;
}

.horizontal-border-1 {
  align-items: flex-start;
  align-self: stretch;
  border-color: var(--ebony);
  border-top-style: solid;
  border-top-width: 1px;
  display: flex;
  height: 53px;
  justify-content: space-between;
  padding: 13px 0.01px 12px 0px;
  position: relative;
  width: 100%;
}

.container-614 {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  gap: 0.01px;
  position: relative;
  width: 100%;
}

.container-575 {
  align-items: flex-end;
  align-self: stretch;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  padding: 0px 0px 0px 8px;
  position: relative;
}

.container-615 {
  align-items: center;
  align-self: stretch;
  display: inline-flex;
  flex: 0 0 auto;
  flex-wrap: wrap;
  gap: 0px 0px;
  justify-content: flex-end;
  padding: 0px 0px 0px 8px;
  position: relative;
}

.border-41 {
  align-items: flex-start;
  align-self: stretch;
  border-bottom-style: solid;
  border-bottom-width: 1px;
  border-color: var(--ebony);
  border-top-style: solid;
  border-top-width: 1px;
  display: flex;
  height: 54px;
  justify-content: space-between;
  padding: 13px 0px;
  position: relative;
  width: 100%;
}

.container-616 {
  align-items: flex-start;
  align-self: stretch;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  min-width: 206.5px;
  padding: 0px 0px 0px 8px;
  position: relative;
}

.container-617 {
  align-items: center;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-wrap: wrap;
  gap: 0px 3.99px;
  justify-content: flex-end;
  margin-bottom: -28px;
  position: relative;
  width: 100%;
}

.container-620 {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  gap: 12px;
  position: relative;
  width: 100%;
}

.btc-converter {
  color: var(--white-lilac);
  font-family: var(--font-family-taviraj);
  font-size: var(--font-size-xxxl);
  font-weight: 700;
  letter-spacing: 0;
  line-height: 28px;
  margin-top: -1px;
  position: relative;
  white-space: nowrap;
  width: fit-content;
}

.container-621 {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  gap: 2px;
  position: relative;
  width: 100%;
}

.container-576 {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  padding: 0px 2px;
  position: relative;
  width: 100%;
}

.background-shadow-26 {
  align-items: flex-start;
  align-self: stretch;
  background-color: var(--black);
  border-radius: 8px 8px 0px 0px;
  box-shadow: 0px 0px 0px 2px #eff2f540;
  display: flex;
  flex: 0 0 auto;
  gap: 4px;
  overflow: hidden;
  position: relative;
  width: 100%;
}

.input-22 {
  align-items: flex-start;
  display: flex;
  flex: 1;
  flex-direction: column;
  flex-grow: 1;
  height: 52px;
  padding: 17.5px 0px 17.5px 8px;
  position: relative;
}

.container-622 {
  align-items: flex-start;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  margin-bottom: -17px;
  overflow: scroll;
  position: relative;
}

.number-61 {
  align-self: stretch;
  color: var(--white);
  font-family: var(--font-family-taviraj);
  font-size: var(--font-size-xxxxl);
  font-weight: 400;
  letter-spacing: 0;
  line-height: normal;
  position: relative;
}

.container-623 {
  align-items: center;
  align-self: stretch;
  display: inline-flex;
  flex: 0 0 auto;
  padding: 15.5px 4px 16.5px;
  position: relative;
}

.background-shadow-27 {
  align-items: flex-start;
  align-self: stretch;
  background-color: var(--black);
  border-radius: 0px 0px 8px 8px;
  box-shadow: 0px 0px 0px 2px #eff2f540;
  display: flex;
  flex: 0 0 auto;
  gap: 4px;
  overflow: hidden;
  position: relative;
  width: 100%;
}

.container-624 {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  margin-bottom: -10px;
  overflow: scroll;
  position: relative;
  width: 100%;
}

.text-344 {
  align-self: stretch;
  letter-spacing: 0;
  line-height: normal;
  position: relative;
}

.container-625 {
  align-items: center;
  align-self: stretch;
  display: inline-flex;
  flex: 0 0 auto;
  padding: 15.5px 4px 16px;
  position: relative;
}

.container-626 {
  align-items: center;
  display: inline-flex;
  flex: 0 0 auto;
  position: relative;
}

.container-627 {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  gap: 24px;
  padding: 0px 0px 24px;
  position: relative;
  width: 100%;
}

.container-577 {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  gap: 16px;
  position: relative;
  width: 100%;
}

.cell-95 {
  align-items: flex-start;
  align-self: stretch;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  justify-content: center;
  padding: 0.5px 1px 1.5px;
  position: relative;
}

.table-body-item {
  align-items: flex-start;
  align-self: stretch;
  border-color: var(--black);
  border-top-style: solid;
  border-top-width: 1px;
  display: flex;
  height: 63px;
  justify-content: space-between;
  padding: 13px 0px 12px;
  position: relative;
  width: 100%;
}

.cell-96 {
  align-items: flex-start;
  align-self: stretch;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  justify-content: center;
  padding: 0.5px 1px 17.5px;
  position: relative;
}

.data-973 {
  align-items: flex-start;
  align-self: stretch;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  padding: 1px 1px 1px 8px;
  position: relative;
}

.container-578 {
  align-items: center;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  gap: 4.4px;
  justify-content: flex-end;
  position: relative;
  width: 100%;
}

.percent-82 {
  color: var(--wwwcoingeckocomred-orange);
  font-weight: 600;
  line-height: 20px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.container-579 {
  align-items: flex-end;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  position: relative;
  width: 100%;
}

.mar-14-2024-7-months,
.jul-06-2013-over-11-years {
  letter-spacing: 0;
  line-height: 16px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.container-629 {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  gap: 4px;
  position: relative;
  width: 100%;
}

.the-community-is-bul {
  align-self: stretch;
  color: var(--screamin-green);
  font-family: var(--font-family-taviraj);
  font-size: var(--font-size-12px);
  font-weight: 400;
  letter-spacing: 0;
  line-height: 16px;
  margin-top: -1px;
  position: relative;
}

.container-631 {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  gap: 3.66px;
  padding: 8px 0px 4px;
  position: relative;
  width: 100%;
}

.rupee-390 {
  height: 15px;
  left: 175px;
  position: absolute;
  top: 1124px;
  width: 9px;
}

.rupee-391 {
  height: 15px;
  left: 293px;
  position: absolute;
  top: 1124px;
  width: 9px;
}

.rupee-392 {
  height: 15px;
  left: 231px;
  position: absolute;
  top: 1218px;
  width: 9px;
}

.rupee-393 {
  height: 15px;
  left: 215px;
  position: absolute;
  top: 1281px;
  width: 9px;
}

.rupee-394 {
  height: 15px;
  left: 214px;
  position: absolute;
  top: 27px;
  width: 9px;
}

.rupee-395 {
  height: 15px;
  left: 214px;
  position: absolute;
  top: 75px;
  width: 9px;
}

.rupee-396 {
  height: 15px;
  left: 231px;
  position: absolute;
  top: 121px;
  width: 9px;
}

.rupee-397 {
  height: 15px;
  left: 0;
  position: absolute;
  top: 153px;
  width: 9px;
}

.container-632 {
  align-items: flex-start;
  display: flex;
  flex-direction: column;
  gap: 16px;
  left: 446px;
  padding: 0px 0px 16px;
  position: absolute;
  top: 773px;
}

.nav {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  gap: 10px;
  overflow: scroll;
  position: relative;
  width: 100%;
}

.component-1-7 {
  align-items: flex-start;
  align-self: stretch;
  background-color: var(--white-4);
  border-radius: 8px;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  padding: 6px 12px;
  position: relative;
}

.container-633 {
  align-self: stretch;
  height: 949.48px;
  max-height: 949.48px;
  overflow: hidden;
  position: relative;
  width: 100%;
  z-index: 1;
}

.container-634 {
  align-items: center;
  display: flex;
  flex-direction: column;
  gap: 4px;
  padding: 0px 0px 420.26px;
  position: relative;
  width: 819px;
}

.bitcoin-13 {
  align-self: stretch;
  letter-spacing: 0;
  line-height: 24px;
  margin-top: -1px;
  position: relative;
}

.heading-3-4 {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  padding: 19.99px 0px 0px;
  position: relative;
  width: 100%;
}

.container-635 {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  padding: 7.99px 0px 0px;
  position: relative;
  width: 100%;
}

.to-learn-more-about {
  align-self: stretch;
  letter-spacing: 0;
  line-height: 18.5px;
  margin-top: -1px;
  position: relative;
}

.list {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  padding: 12px 0px 0px;
  position: relative;
  width: 100%;
}

.item-1 {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  margin-top: -1.78e-14px;
  position: relative;
  width: 100%;
}

.heading-3-5 {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  padding: 20px 0px 0px;
  position: relative;
  width: 100%;
}

.how-to-keep-your-bitcoin-safe {
  align-self: stretch;
  color: #334155;
  font-family: var(--font-family-inter);
  font-size: var(--font-size-xl);
  font-weight: 600;
  letter-spacing: 0;
  line-height: 24px;
  margin-top: -1px;
  position: relative;
}

.container-636 {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  padding: 0px 0px 18.77px;
  position: relative;
  width: 100%;
}

.whentransacting-coi {
  align-self: stretch;
  color: #64748b;
  font-family: var(--font-family-inter);
  font-size: var(--font-size-s);
  font-weight: 400;
  letter-spacing: 0;
  line-height: 18.5px;
  margin-top: -1px;
  position: relative;
}

.container-637 {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  position: relative;
  width: 100%;
  z-index: 0;
}

.component-3-42 {
  align-items: center;
  background-color: var(--ebony);
  border: 1px solid;
  border-color: var(--mischka);
  border-radius: 8px;
  display: inline-flex;
  flex: 0 0 auto;
  justify-content: center;
  padding: 6px 10px;
  position: relative;
}

.make-a-ad-image {
  background-position: 50% 50%;
  background-size: cover;
  height: 250px;
  left: 29px;
  position: absolute;
  top: 1791px;
  width: 336px;
}

.overlap-group6-13 {
  height: 784px;
  margin-top: 192px;
  position: relative;
  width: 1402px;
}

.social-icons-168 {
  height: 24px;
  left: 1085px;
  position: absolute;
  top: 241px;
  width: 24px;
}

.line-114-23 {
  height: 1px;
  left: 0;
  object-fit: cover;
  position: absolute;
  top: 131px;
  width: 1402px;
}

.frame-14399 {
  align-items: center;
  display: flex;
  flex-direction: column;
  height: 784px;
  left: 0;
  position: absolute;
  top: 0;
  width: 1402px;
}

.frame-14398 {
  flex: 0 0 auto;
  position: relative;
  width: 1286px;
}

.rectangle-5227-21 {
  align-self: stretch;
  background-color: var(--mirage);
  border-radius: 30px;
  height: 368px;
  margin-top: -507px;
  position: relative;
  width: 100%;
}

.social-icons-169 {
  height: 24px;
  left: 1257px;
  position: absolute;
  top: 203px;
  width: 24px;
}

.social-icons-170 {
  height: 24px;
  left: 1214px;
  position: absolute;
  top: 204px;
  width: 24px;
}

.social-icons-171 {
  height: 24px;
  left: 1171px;
  position: absolute;
  top: 204px;
  width: 24px;
}

.social-icons-172 {
  height: 24px;
  left: 1128px;
  position: absolute;
  top: 204px;
  width: 24px;
}

.social-icons-173 {
  height: 24px;
  left: 1042px;
  position: absolute;
  top: 204px;
  width: 24px;
}

.social-icons-174 {
  height: 24px;
  left: 1300px;
  position: absolute;
  top: 204px;
  width: 24px;
}

.social-icons-175 {
  height: 24px;
  left: 999px;
  position: absolute;
  top: 204px;
  width: 24px;
}

.follow-us-21 {
  height: 20px;
  left: 899px;
  letter-spacing: 0;
  line-height: 20px;
  position: absolute;
  text-align: center;
  top: 203px;
  white-space: nowrap;
  width: 108px;
}

.email-22 {
  height: 19px;
  left: 899px;
  letter-spacing: 0;
  line-height: 20px;
  position: absolute;
  text-align: center;
  top: 240px;
  white-space: nowrap;
  width: 92px;
}

.abc123gmailcom-21 {
  height: 32px;
  left: 959px;
  letter-spacing: 0;
  line-height: 20px;
  position: absolute;
  text-align: center;
  top: 234px;
  width: 143px;
}

.about-us-21 {
  height: 43px;
  left: 431px;
  letter-spacing: 0;
  line-height: 20px;
  position: absolute;
  text-align: center;
  top: 208px;
  width: 90px;
}

.company-name-and-symbol-21 {
  height: 58px;
  left: 104px;
  letter-spacing: 0;
  line-height: 20px;
  position: absolute;
  top: 196px;
  width: 145px;
}

.privacy-policy-21 {
  height: 46px;
  left: 547px;
  letter-spacing: 0;
  line-height: 20px;
  position: absolute;
  text-align: center;
  top: 206px;
  width: 260px;
}

.terms-of-use-21 {
  height: 47px;
  left: 707px;
  letter-spacing: 0;
  line-height: 20px;
  position: absolute;
  text-align: center;
  top: 205px;
  width: 188px;
}

.all-content-on-abcc-21 {
  left: 77px;
  letter-spacing: 0;
  line-height: 44px;
  position: absolute;
  top: 275px;
  width: 1283px;
}

.rectangle-5218-19 {
  background-color: var(--dhancowhite);
  border-radius: 40px;
  height: 490px;
  margin-top: 15px;
  width: 6px;
}

.rectangle-5217-19 {
  background-color: var(--white-2);
  border-radius: 10px;
  height: 2746px;
  margin-top: 58px;
  width: 6px;
}
</style>
