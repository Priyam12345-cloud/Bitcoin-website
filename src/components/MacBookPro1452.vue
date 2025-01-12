<template>
  <div class="container-center-horizontal">
    <div class="macbook-pro-14u34-52 screen">
      <img class="gradient-blur-7" :src="gradientBlur" alt="Gradient+Blur" />
      <div class="flex-col-6">
        <h1 class="surname-13 valign-text-middle taviraj-semi-bold-white-36px">{{ surname }}</h1>
        <div class="overlap-group11-3" :style="{ 'background-image': 'url(' + overlapGroup11 + ')' }">
          <div class="portfolio-2 valign-text-middle taviraj-bold-white-14px">{{ portfolio2 }}</div>
        </div>
        <img class="line-2-3" :src="line2" alt="Line 2" />
        <div class="coins-pool valign-text-middle">{{ coinsPool }}</div>
        <div class="overlap-group19-1" :style="{ 'background-image': 'url(' + overlapGroup19 + ')' }">
          <div class="text-11-1 valign-text-middle taviraj-medium-white-16px">{{ text6 }}</div>
          <img class="ic_btc-4" :src="ic_Btc" alt="ic_btc" />
          <div class="bitcoin-7 valign-text-middle taviraj-semi-bold-white-20px">{{ bitcoin1 }}</div>
          <img class="users-02-1" :src="users021" alt="users-02" />
          <div class="percent-48 valign-text-middle taviraj-semi-bold-white-16px">{{ percent1 }}</div>
        </div>
        <div class="overlap-group-19" :style="{ 'background-image': 'url(' + overlapGroup4 + ')' }">
          <div class="text-11-1 valign-text-middle taviraj-medium-white-16px">{{ text7 }}</div>
          <img class="ic_eth-3" :src="ic_Eth" alt="ic_eth" />
          <div class="etherum-2 valign-text-middle taviraj-semi-bold-white-20px">{{ etherum1 }}</div>
          <img class="users-02-2" :src="users022" alt="users-02" />
          <div class="percent-49 valign-text-middle taviraj-semi-bold-white-16px">{{ percent2 }}</div>
        </div>
        <div class="overlap-group16-1" :style="{ 'background-image': 'url(' + overlapGroup16 + ')' }">
          <div class="text-11-2 valign-text-middle taviraj-medium-white-16px">{{ text8 }}</div>
          <img class="ic_usdt-2" :src="ic_Usdt" alt="ic_usdt" />
          <div class="tether-3 valign-text-middle taviraj-semi-bold-white-20px">{{ tether1 }}</div>
          <img class="users-02-3" :src="users023" alt="users-02" />
          <div class="percent-49 valign-text-middle taviraj-semi-bold-white-16px">{{ percent3 }}</div>
        </div>
        <div class="overlap-group-21" :style="{ 'background-image': 'url(' + overlapGroup + ')' }">
          <div class="text-11-2 valign-text-middle taviraj-medium-white-16px">{{ text9 }}</div>
          <img class="ic_xrp-1" :src="ic_Xrp" alt="ic_xrp" />
          <div class="xrp-3 valign-text-middle taviraj-semi-bold-white-20px">{{ xrp }}</div>
          <img class="users-02-4" :src="users024" alt="users-02" />
          <div class="percent-48 valign-text-middle taviraj-semi-bold-white-16px">{{ percent4 }}</div>
        </div>
        <div class="overlap-group6-4" :style="{ 'background-image': 'url(' + overlapGroup6 + ')' }">
          <div class="text-11-1 valign-text-middle taviraj-medium-white-16px">{{ text10 }}</div>
          <img class="ic_sol-1" :src="ic_Sol" alt="ic_sol" />
          <div class="solana-2 valign-text-middle taviraj-semi-bold-white-20px">{{ solana }}</div>
          <img class="users-02" :src="users025" alt="users-02" />
          <div class="percent-50 valign-text-middle taviraj-semi-bold-white-16px">{{ percent5 }}</div>
        </div>
        <div class="overlap-group7-5" :style="{ 'background-image': 'url(' + overlapGroup7 + ')' }">
          <div class="text-116 valign-text-middle taviraj-medium-white-16px">{{ text11 }}</div>
          <img class="ic_avax-1" :src="ic_Avax" alt="ic_avax" />
          <div class="avalanche-2 valign-text-middle taviraj-semi-bold-white-16px">{{ avalanche }}</div>
          <img class="users-02-5" :src="users026" alt="users-02" />
          <div class="percent-51 valign-text-middle taviraj-semi-bold-white-16px">{{ percent6 }}</div>
        </div>
        <div class="overlap-group-19" :style="{ 'background-image': 'url(' + overlapGroup18 + ')' }">
          <div class="text-11-1 valign-text-middle taviraj-medium-white-16px">{{ text12 }}</div>
          <img class="ic_ada-2" :src="ic_Ada" alt="ic_ada" />
          <div class="place-31 valign-text-middle taviraj-semi-bold-white-16px">{{ place }}</div>
          <img class="users-02" :src="users027" alt="users-02" />
          <div class="percent-50 valign-text-middle taviraj-semi-bold-white-16px">{{ percent7 }}</div>
        </div>
        <div class="overlap-group3-5" :style="{ 'background-image': 'url(' + overlapGroup3 + ')' }">
          <div class="text-119 valign-text-middle taviraj-medium-white-16px">{{ text14 }}</div>
          <img class="ic_uni-2" :src="ic_Uni" alt="ic_uni" />
          <div class="uniswap-2 valign-text-middle taviraj-semi-bold-white-16px">{{ uniswap }}</div>
          <img class="users-02-6" :src="users028" alt="users-02" />
          <div class="percent-52 valign-text-middle taviraj-semi-bold-white-16px">{{ percent8 }}</div>
        </div>
        <div class="overlap-group-19" :style="{ 'background-image': 'url(' + overlapGroup20 + ')' }">
          <div class="text-120 valign-text-middle taviraj-medium-white-16px">{{ text15 }}</div>
          <img class="ic_trx-1" :src="ic_Trx" alt="ic_trx" />
          <div class="tron-2 valign-text-middle taviraj-semi-bold-white-16px">{{ tron }}</div>
          <img class="users-02-7" :src="users029" alt="users-02" />
          <div class="percent-50 valign-text-middle taviraj-semi-bold-white-16px">{{ percent9 }}</div>
        </div>
        <div
          class="overlap-group1-8 taviraj-semi-bold-white-16px"
          :style="{ 'background-image': 'url(' + overlapGroup17 + ')' }"
        >
          <div class="overlap-group2-8">
            <div class="text-1-4 valign-text-middle taviraj-medium-white-16px">{{ text13 }}</div>
            <img class="ic_polygon-1" :src="ic_Polygon" alt="ic_polygon" />
          </div>
          <div class="polygon-1 valign-text-middle">{{ polygon }}</div>
          <img class="users-02-8" :src="users0210" alt="users-02" />
          <div class="percent-50 valign-text-middle">{{ percent10 }}</div>
        </div>
        <div
          class="overlap-group9-5 taviraj-semi-bold-white-16px"
          :style="{ 'background-image': 'url(' + overlapGroup9 + ')' }"
        >
          <div class="overlap-group2-9">
            <div class="text-12-1 valign-text-middle taviraj-medium-white-16px">{{ text16 }}</div>
            <img class="ic_xem-1" :src="ic_Xem" alt="ic_xem" />
          </div>
          <div class="nem-1 valign-text-middle">{{ nem }}</div>
          <img class="users-02-9" :src="users0211" alt="users-02" />
          <div class="percent-51 valign-text-middle">{{ percent11 }}</div>
        </div>
        <div class="overlap-group1-9" :style="{ 'background-image': 'url(' + overlapGroup13 + ')' }">
          <div class="overlap-group2-8">
            <div class="text-12-1 valign-text-middle taviraj-medium-white-16px">{{ text17 }}</div>
            <img class="ic_cake-2" :src="ic_Cake" alt="ic_cake" />
          </div>
          <div class="overlap-group24">
            <div class="pancanke-swap-1 valign-text-middle taviraj-semi-bold-white-14px">{{ pancankeswap }}</div>
            <img class="users-02-10" :src="users0212" alt="users-02" />
          </div>
          <div class="percent-50 valign-text-middle taviraj-semi-bold-white-16px">{{ percent12 }}</div>
        </div>
        <div
          class="overlap-group1-9 taviraj-semi-bold-white-16px"
          :style="{ 'background-image': 'url(' + overlapGroup14 + ')' }"
        >
          <div class="overlap-group2-9">
            <div class="text-12-1 valign-text-middle taviraj-medium-white-16px">{{ text18 }}</div>
            <img class="ic_bnb_2-1" :src="ic_Bnb_2" alt="ic_bnb_2" />
          </div>
          <div class="bnb-4 valign-text-middle">{{ bnb1 }}</div>
          <img class="users-02-11" :src="users0213" alt="users-02" />
          <div class="percent-50 valign-text-middle">{{ percent13 }}</div>
        </div>
        <div
          class="overlap-group1-8 taviraj-semi-bold-white-16px"
          :style="{ 'background-image': 'url(' + overlapGroup15 + ')' }"
        >
          <div class="overlap-group2-8">
            <div class="text-1-4 valign-text-middle taviraj-medium-white-16px">{{ text19 }}</div>
            <img class="ic_btrst-1" :src="ic_Btrst" alt="ic_btrst" />
          </div>
          <div class="brain-trust-1 valign-text-middle">{{ braintrust }}</div>
          <img class="users-02-12" :src="users0214" alt="users-02" />
          <div class="percent-51 valign-text-middle">{{ percent14 }}</div>
        </div>
      </div>
      <img class="line-1-3" :src="line1" alt="Line 1" />
      <div class="overlap-group-container">
        <div class="overlap-group12-2">
          <div class="overlap-group27">
            <p class="total-invested-644350 valign-text-middle taviraj-semi-bold-white-20px">
              {{ totalInvested644350 }}
            </p>
            <img class="rupee-217" :src="rupee1" alt="Rupee" />
          </div>
          <p class="total-profit-144350-312 valign-text-middle">
            <span
              ><span class="taviraj-semi-bold-white-20px">{{ spanText1 }}</span
              ><span class="taviraj-semi-bold-screamin-green-20px">{{ spanText2 }}</span
              ><span class="taviraj-semi-bold-screamin-green-15px">{{ spanText3 }}</span
              ><span class="taviraj-semi-bold-white-15px">{{ spanText4 }}</span>
            </span>
          </p>
          <div class="rank-20 valign-text-middle taviraj-semi-bold-white-20px">{{ rank20 }}</div>
        </div>
        <div class="overlap-group2-10">
          <div class="rectangle"></div>
          <img class="line-28" :src="line3" alt="Line 3" />
          <div class="bitcoin-8 valign-text-middle taviraj-extra-bold-white-23px">{{ bitcoin2 }}</div>
          <p class="total-invested-644350-1 valign-text-middle taviraj-semi-bold-white-17px-2">
            <span
              ><span class="taviraj-semi-bold-white-17px">{{ spanText5 }}</span
              ><span class="taviraj-semi-bold-white-20px">{{ spanText6 }}</span
              ><span class="taviraj-semi-bold-lemon-20px">{{ spanText7 }}</span>
            </span>
          </p>
          <div class="quantity-bought-0032 valign-text-middle taviraj-semi-bold-white-17px-2">
            <span
              ><span class="taviraj-semi-bold-white-17px">{{ spanText8 }}</span
              ><span class="taviraj-semi-bold-white-20px">{{ spanText9 }}</span
              ><span class="taviraj-semi-bold-lemon-20px">{{ spanText10 }}</span>
            </span>
          </div>
          <p class="current-value-806452 valign-text-middle taviraj-semi-bold-white-17px-2">
            <span
              ><span class="taviraj-semi-bold-white-17px">{{ spanText11 }}</span
              ><span class="taviraj-semi-bold-white-20px">{{ spanText12 }}</span
              ><span class="taviraj-semi-bold-lemon-20px">{{ spanText13 }}</span>
            </span>
          </p>
          <p class="pl-5110022-312 valign-text-middle taviraj-semi-bold-white-17px-2">
            <span
              ><span class="taviraj-semi-bold-screamin-green-17px">{{ spanText14 }}</span
              ><span class="taviraj-semi-bold-screamin-green-20px">{{ spanText15 }}</span
              ><span class="taviraj-semi-bold-lemon-20px">{{ spanText16 }}</span
              ><span class="taviraj-semi-bold-screamin-green-25px">{{ spanText17 }}</span
              ><span class="taviraj-semi-bold-screamin-green-13px">{{ spanText18 }}</span
              ><span class="taviraj-semi-bold-screamin-green-15px">{{ spanText19 }}</span>
            </span>
          </p>
          <img class="rupee-218" :src="rupee2" alt="Rupee" /><img class="rupee-219" :src="rupee3" alt="Rupee" /><img
            class="rupee-220"
            :src="rupee4"
            alt="Rupee"
          /><img class="btc-9" :src="btc" alt="btc" />
        </div>
        <div class="overlap-group-20">
          <div class="rectangle"></div>
          <img class="line-28" :src="line4" alt="Line 4" />
          <div class="bnb-5 valign-text-middle taviraj-extra-bold-white-23px">{{ bnb2 }}</div>
          <p class="total-invested-644350-2 valign-text-middle taviraj-semi-bold-white-17px-2">
            <span
              ><span class="taviraj-semi-bold-white-17px">{{ spanText20 }}</span
              ><span class="taviraj-semi-bold-white-20px">{{ spanText21 }}</span
              ><span class="taviraj-semi-bold-lemon-20px">{{ spanText22 }}</span>
            </span>
          </p>
          <div class="quantity-bought-42 valign-text-middle taviraj-semi-bold-white-17px-2">
            <span
              ><span class="taviraj-semi-bold-white-17px">{{ spanText23 }}</span
              ><span class="taviraj-semi-bold-white-20px">{{ spanText24 }}</span
              ><span class="taviraj-semi-bold-lemon-20px">{{ spanText25 }}</span>
            </span>
          </div>
          <p class="current-value-806452-1 valign-text-middle taviraj-semi-bold-white-17px-2">
            <span
              ><span class="taviraj-semi-bold-white-17px">{{ spanText26 }}</span
              ><span class="taviraj-semi-bold-white-20px">{{ spanText27 }}</span
              ><span class="taviraj-semi-bold-lemon-20px">{{ spanText28 }}</span>
            </span>
          </p>
          <p class="pl-5110022-312-1 valign-text-middle taviraj-semi-bold-white-17px-2">
            <span
              ><span class="taviraj-semi-bold-screamin-green-17px">{{ spanText29 }}</span
              ><span class="taviraj-semi-bold-screamin-green-20px">{{ spanText30 }}</span
              ><span class="taviraj-semi-bold-lemon-20px">{{ spanText31 }}</span
              ><span class="taviraj-semi-bold-screamin-green-25px">{{ spanText32 }}</span
              ><span class="taviraj-semi-bold-screamin-green-13px">{{ spanText33 }}</span>
            </span>
          </p>
          <img class="rupee-221" :src="rupee5" alt="Rupee" /><img class="rupee-222" :src="rupee6" alt="Rupee" /><img
            class="rupee-223"
            :src="rupee7"
            alt="Rupee"
          /><img class="bnb-6" :src="bnb3" alt="bnb" />
        </div>
        <div class="overlap-group-20">
          <div class="rectangle"></div>
          <img class="line-28" :src="line5" alt="Line 5" />
          <div class="etherum-3 valign-text-middle taviraj-extra-bold-white-23px">{{ etherum2 }}</div>
          <p class="total-invested-644350-3 valign-text-middle taviraj-semi-bold-white-17px-2">
            <span
              ><span class="taviraj-semi-bold-white-17px">{{ spanText34 }}</span
              ><span class="taviraj-semi-bold-white-20px">{{ spanText35 }}</span
              ><span class="taviraj-semi-bold-lemon-20px">{{ spanText36 }}</span>
            </span>
          </p>
          <div class="quantity-bought-078 valign-text-middle taviraj-semi-bold-white-17px-2">
            <span
              ><span class="taviraj-semi-bold-white-17px">{{ spanText37 }}</span
              ><span class="taviraj-semi-bold-white-20px">{{ spanText38 }}</span
              ><span class="taviraj-semi-bold-lemon-20px">{{ spanText39 }}</span>
            </span>
          </div>
          <p class="current-value-806452-2 valign-text-middle taviraj-semi-bold-white-17px-2">
            <span
              ><span class="taviraj-semi-bold-white-17px">{{ spanText40 }}</span
              ><span class="taviraj-semi-bold-white-20px">{{ spanText41 }}</span
              ><span class="taviraj-semi-bold-lemon-20px">{{ spanText42 }}</span>
            </span>
          </p>
          <p class="pl-1110022-134 valign-text-middle taviraj-semi-bold-white-17px-2">
            <span
              ><span class="span0-2">{{ spanText43 }}</span
              ><span class="span1-3">{{ spanText44 }}</span
              ><span class="taviraj-semi-bold-screamin-green-20px">{{ spanText45 }}</span
              ><span class="taviraj-semi-bold-lemon-20px">{{ spanText46 }}</span
              ><span class="taviraj-semi-bold-screamin-green-25px">{{ spanText47 }}</span
              ><span class="span5">{{ spanText48 }}</span
              ><span class="taviraj-semi-bold-red-orange-15px">{{ spanText49 }}</span>
            </span>
          </p>
          <img class="rupee-224" :src="rupee8" alt="Rupee" /><img class="rupee-225" :src="rupee9" alt="Rupee" /><img
            class="rupee-226"
            :src="rupee10"
            alt="Rupee"
          /><img class="eth" :src="eth" alt="eth" />
        </div>
        <div class="overlap-group5-4">
          <div class="rectangle"></div>
          <img class="line-28" :src="line6" alt="Line 6" />
          <div class="tether-4 valign-text-middle taviraj-extra-bold-white-23px">{{ tether2 }}</div>
          <p class="total-invested-644350-4 valign-text-middle taviraj-semi-bold-white-17px-2">
            <span
              ><span class="taviraj-semi-bold-white-17px">{{ spanText50 }}</span
              ><span class="taviraj-semi-bold-white-20px">{{ spanText51 }}</span
              ><span class="taviraj-semi-bold-lemon-20px">{{ spanText52 }}</span>
            </span>
          </p>
          <div class="quantity-bought-100 valign-text-middle taviraj-semi-bold-white-17px-2">
            <span
              ><span class="taviraj-semi-bold-white-17px">{{ spanText53 }}</span
              ><span class="taviraj-semi-bold-white-20px">{{ spanText54 }}</span
              ><span class="taviraj-semi-bold-lemon-20px">{{ spanText55 }}</span>
            </span>
          </div>
          <p class="current-value-806452-3 valign-text-middle taviraj-semi-bold-white-17px-2">
            <span
              ><span class="taviraj-semi-bold-white-17px">{{ spanText56 }}</span
              ><span class="taviraj-semi-bold-white-20px">{{ spanText57 }}</span
              ><span class="taviraj-semi-bold-lemon-20px">{{ spanText58 }}</span>
            </span>
          </p>
          <p class="pl-5110022-312-2 valign-text-middle taviraj-semi-bold-white-17px-2">
            <span
              ><span class="taviraj-semi-bold-screamin-green-17px">{{ spanText59 }}</span
              ><span class="taviraj-semi-bold-screamin-green-20px">{{ spanText60 }}</span
              ><span class="taviraj-semi-bold-lemon-20px">{{ spanText61 }}</span
              ><span class="taviraj-semi-bold-screamin-green-25px">{{ spanText62 }}</span
              ><span class="taviraj-semi-bold-screamin-green-13px">{{ spanText63 }}</span>
            </span>
          </p>
          <img class="rupee-227" :src="rupee11" alt="Rupee" /><img class="rupee-228" :src="rupee12" alt="Rupee" /><img
            class="rupee-229"
            :src="rupee13"
            alt="Rupee"
          /><img class="usdt-1" :src="usdt" alt="usdt" />
        </div>
      </div>
      <div class="overlap-group10-4">
        <div class="rectangle-5205-1"></div>
        <div class="rectangle-5206-1"></div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "MacBookPro1452",
  props: [
    "gradientBlur",
    "surname",
    "overlapGroup11",
    "portfolio2",
    "line2",
    "coinsPool",
    "overlapGroup19",
    "text6",
    "ic_Btc",
    "bitcoin1",
    "users021",
    "percent1",
    "overlapGroup4",
    "text7",
    "ic_Eth",
    "etherum1",
    "users022",
    "percent2",
    "overlapGroup16",
    "text8",
    "ic_Usdt",
    "tether1",
    "users023",
    "percent3",
    "overlapGroup",
    "text9",
    "ic_Xrp",
    "xrp",
    "users024",
    "percent4",
    "overlapGroup6",
    "text10",
    "ic_Sol",
    "solana",
    "users025",
    "percent5",
    "overlapGroup7",
    "text11",
    "ic_Avax",
    "avalanche",
    "users026",
    "percent6",
    "overlapGroup18",
    "text12",
    "ic_Ada",
    "place",
    "users027",
    "percent7",
    "overlapGroup3",
    "text14",
    "ic_Uni",
    "uniswap",
    "users028",
    "percent8",
    "overlapGroup20",
    "text15",
    "ic_Trx",
    "tron",
    "users029",
    "percent9",
    "overlapGroup17",
    "text13",
    "ic_Polygon",
    "polygon",
    "users0210",
    "percent10",
    "overlapGroup9",
    "text16",
    "ic_Xem",
    "nem",
    "users0211",
    "percent11",
    "overlapGroup13",
    "text17",
    "ic_Cake",
    "pancankeswap",
    "users0212",
    "percent12",
    "overlapGroup14",
    "text18",
    "ic_Bnb_2",
    "bnb1",
    "users0213",
    "percent13",
    "overlapGroup15",
    "text19",
    "ic_Btrst",
    "braintrust",
    "users0214",
    "percent14",
    "line1",
    "totalInvested644350",
    "rupee1",
    "spanText1",
    "spanText2",
    "spanText3",
    "spanText4",
    "rank20",
    "line3",
    "bitcoin2",
    "spanText5",
    "spanText6",
    "spanText7",
    "spanText8",
    "spanText9",
    "spanText10",
    "spanText11",
    "spanText12",
    "spanText13",
    "spanText14",
    "spanText15",
    "spanText16",
    "spanText17",
    "spanText18",
    "spanText19",
    "rupee2",
    "rupee3",
    "rupee4",
    "btc",
    "line4",
    "bnb2",
    "spanText20",
    "spanText21",
    "spanText22",
    "spanText23",
    "spanText24",
    "spanText25",
    "spanText26",
    "spanText27",
    "spanText28",
    "spanText29",
    "spanText30",
    "spanText31",
    "spanText32",
    "spanText33",
    "rupee5",
    "rupee6",
    "rupee7",
    "bnb3",
    "line5",
    "etherum2",
    "spanText34",
    "spanText35",
    "spanText36",
    "spanText37",
    "spanText38",
    "spanText39",
    "spanText40",
    "spanText41",
    "spanText42",
    "spanText43",
    "spanText44",
    "spanText45",
    "spanText46",
    "spanText47",
    "spanText48",
    "spanText49",
    "rupee8",
    "rupee9",
    "rupee10",
    "eth",
    "line6",
    "tether2",
    "spanText50",
    "spanText51",
    "spanText52",
    "spanText53",
    "spanText54",
    "spanText55",
    "spanText56",
    "spanText57",
    "spanText58",
    "spanText59",
    "spanText60",
    "spanText61",
    "spanText62",
    "spanText63",
    "rupee11",
    "rupee12",
    "rupee13",
    "usdt",
  ],
};
</script>

<style>
.macbook-pro-14u34-52 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  overflow: hidden;
  width: 1298px;
}

.gradient-blur-7 {
  height: 102px;
  margin-left: -3455px;
  margin-top: 2446.51px;
  width: 141px;
}

.flex-col-6 {
  align-items: center;
  display: flex;
  flex-direction: column;
  margin-left: 3314px;
  margin-top: 32px;
  min-height: 944px;
  width: 300px;
}

.surname-13 {
  height: 34px;
  letter-spacing: 0;
  line-height: 16px;
  margin-right: 9px;
  width: 145px;
}

.overlap-group11-3 {
  align-items: flex-start;
  align-self: flex-end;
  background-size: 100% 100%;
  display: flex;
  height: 29px;
  justify-content: flex-end;
  margin-right: 30px;
  margin-top: 14px;
  min-width: 112px;
  padding: 1px 4.5px;
}

.portfolio-2 {
  height: 25px;
  letter-spacing: 0;
  line-height: normal;
  text-align: center;
  width: 102px;
}

.line-2-3 {
  height: 1px;
  margin-top: 20px;
  object-fit: cover;
  width: 300px;
}

.coins-pool {
  -webkit-background-clip: text !important;
  -webkit-text-fill-color: transparent;
  align-self: flex-start;
  background: linear-gradient(
    180deg,
    rgb(249, 217, 5) 0%,
    rgba(252, 236, 130, 0.8) 50%,
    rgb(253, 245, 193) 75%,
    rgba(255, 255, 255, 0.8) 100%
  );
  background-clip: text;
  color: transparent;
  font-family: var(--font-family-taviraj);
  font-size: 30px;
  font-weight: 700;
  height: 50px;
  letter-spacing: 0;
  line-height: 32px;
  margin-left: 10px;
  margin-top: 8px;
  text-fill-color: transparent;
  width: 177px;
}

.overlap-group19-1 {
  align-items: center;
  background-size: 100% 100%;
  display: flex;
  height: 43px;
  margin-left: 2px;
  margin-top: 5px;
  min-width: 282px;
  padding: 6px 11px;
}

.text-11-1 {
  height: 20px;
  letter-spacing: 0;
  line-height: 20px;
  margin-bottom: 1px;
  width: 16px;
}

.ic_btc-4,
.ic_eth-3,
.ic_usdt-2,
.ic_xrp-1,
.ic_avax-1,
.ic_ada-2 {
  align-self: flex-end;
  height: 30px;
  margin-left: 4px;
  width: 30px;
}

.bitcoin-7 {
  height: 20px;
  letter-spacing: 0;
  line-height: 20px;
  margin-bottom: 1px;
  margin-left: 9px;
  width: 85px;
}

.users-02-1 {
  height: 24px;
  margin-left: 29px;
  margin-top: 3px;
  width: 24px;
}

.percent-48 {
  height: 15px;
  letter-spacing: 0;
  line-height: 20px;
  margin-left: 4px;
  white-space: nowrap;
  width: 43px;
}

.overlap-group-19 {
  align-items: center;
  background-size: 100% 100%;
  display: flex;
  height: 43px;
  margin-left: 2px;
  margin-top: 15px;
  min-width: 282px;
  padding: 6px 11px;
}

.etherum-2 {
  height: 20px;
  letter-spacing: 0;
  line-height: 20px;
  margin-bottom: 1px;
  margin-left: 7px;
  width: 104px;
}

.users-02-2 {
  align-self: flex-end;
  height: 24px;
  margin-bottom: 1px;
  margin-left: 12px;
  width: 24px;
}

.percent-49 {
  height: 15px;
  letter-spacing: 0;
  line-height: 20px;
  margin-left: 4px;
  margin-top: 2px;
  white-space: nowrap;
  width: 43px;
}

.overlap-group16-1 {
  align-items: center;
  background-size: 100% 100%;
  display: flex;
  height: 43px;
  margin-left: 2px;
  margin-top: 12px;
  min-width: 282px;
  padding: 6px 10px;
}

.text-11-2 {
  height: 20px;
  letter-spacing: 0;
  line-height: 20px;
  margin-bottom: 1px;
  width: 17px;
}

.tether-3 {
  height: 20px;
  letter-spacing: 0;
  line-height: 20px;
  margin-bottom: 1px;
  margin-left: 7px;
  width: 79px;
}

.users-02-3 {
  align-self: flex-end;
  height: 24px;
  margin-bottom: 1px;
  margin-left: 37px;
  width: 24px;
}

.overlap-group-21 {
  align-items: center;
  background-size: 100% 100%;
  display: flex;
  height: 43px;
  margin-left: 2px;
  margin-top: 14px;
  min-width: 282px;
  padding: 6px 10px;
}

.xrp-3 {
  height: 20px;
  letter-spacing: 0;
  line-height: 20px;
  margin-bottom: 1px;
  margin-left: 9px;
  width: 49px;
}

.users-02-4 {
  height: 24px;
  margin-left: 65px;
  margin-top: 3px;
  width: 24px;
}

.overlap-group6-4 {
  align-items: center;
  background-size: 100% 100%;
  display: flex;
  height: 43px;
  margin-left: 2px;
  margin-top: 14px;
  min-width: 282px;
  padding: 5px 11px;
}

.ic_sol-1,
.ic_trx-1 {
  align-self: flex-start;
  height: 30px;
  margin-left: 4px;
  width: 30px;
}

.solana-2,
.place-31 {
  height: 20px;
  letter-spacing: 0;
  line-height: 20px;
  margin-bottom: 1px;
  margin-left: 7px;
  width: 80px;
}

.users-02 {
  height: 24px;
  margin-left: 36px;
  margin-top: 1px;
  width: 24px;
}

.percent-50 {
  height: 15px;
  letter-spacing: 0;
  line-height: 20px;
  margin-bottom: 2px;
  margin-left: 4px;
  white-space: nowrap;
  width: 43px;
}

.overlap-group7-5 {
  align-items: center;
  background-size: 100% 100%;
  display: flex;
  height: 43px;
  margin-left: 2px;
  margin-top: 13px;
  min-width: 282px;
  padding: 6px 11px;
}

.text-116 {
  height: 20px;
  letter-spacing: 0;
  line-height: 20px;
  margin-top: 1px;
  width: 16px;
}

.avalanche-2 {
  height: 20px;
  letter-spacing: 0;
  line-height: 20px;
  margin-left: 7px;
  margin-top: 1px;
  width: 97px;
}

.users-02-5 {
  height: 24px;
  margin-bottom: 1px;
  margin-left: 19px;
  width: 24px;
}

.percent-51 {
  height: 15px;
  letter-spacing: 0;
  line-height: 20px;
  margin-bottom: 4px;
  margin-left: 4px;
  white-space: nowrap;
  width: 43px;
}

.overlap-group3-5 {
  align-items: flex-start;
  background-size: 100% 100%;
  display: flex;
  height: 43px;
  margin-left: 2px;
  margin-top: 14px;
  min-width: 282px;
  padding: 6px 11px;
}

.text-119 {
  align-self: center;
  height: 20px;
  letter-spacing: 0;
  line-height: 20px;
  margin-top: 1px;
  width: 16px;
}

.ic_uni-2 {
  height: 30px;
  margin-left: 4px;
  width: 30px;
}

.uniswap-2 {
  align-self: center;
  height: 20px;
  letter-spacing: 0;
  line-height: 20px;
  margin-left: 7px;
  margin-top: 1px;
  width: 80px;
}

.users-02-6 {
  height: 24px;
  margin-left: 36px;
  margin-top: 1px;
  width: 24px;
}

.percent-52 {
  height: 15px;
  letter-spacing: 0;
  line-height: 20px;
  margin-left: 4px;
  margin-top: 4px;
  white-space: nowrap;
}

.text-120 {
  height: 20px;
  letter-spacing: 0;
  line-height: 20px;
  margin-bottom: 3px;
  width: 16px;
}

.tron-2 {
  height: 20px;
  letter-spacing: 0;
  line-height: 20px;
  margin-bottom: 3px;
  margin-left: 7px;
  width: 55px;
}

.users-02-7 {
  height: 24px;
  margin-left: 61px;
  margin-top: 1px;
  width: 24px;
}

.overlap-group1-8 {
  align-items: center;
  background-size: 100% 100%;
  display: flex;
  height: 43px;
  margin-left: 2px;
  margin-top: 13px;
  min-width: 282px;
  padding: 6px 7px;
}

.overlap-group2-8 {
  align-self: flex-end;
  height: 30px;
  position: relative;
  width: 54px;
}

.text-1-4 {
  height: 20px;
  left: 0;
  letter-spacing: 0;
  line-height: 20px;
  position: absolute;
  top: 4px;
  width: 28px;
}

.ic_polygon-1,
.ic_xem-1,
.ic_cake-2,
.ic_bnb_2-1,
.ic_btrst-1 {
  height: 30px;
  left: 24px;
  position: absolute;
  top: 0;
  width: 30px;
}

.polygon-1 {
  height: 20px;
  letter-spacing: 0;
  line-height: 20px;
  margin-bottom: 1px;
  margin-left: 7px;
  width: 76px;
}

.users-02-8 {
  height: 24px;
  margin-left: 40px;
  margin-top: 1px;
  width: 24px;
}

.overlap-group9-5 {
  align-items: center;
  background-size: 100% 100%;
  display: flex;
  height: 43px;
  margin-left: 2px;
  margin-top: 15px;
  min-width: 282px;
  padding: 6px 7px;
}

.overlap-group2-9 {
  align-self: flex-start;
  height: 30px;
  position: relative;
  width: 54px;
}

.text-12-1 {
  height: 20px;
  left: 0;
  letter-spacing: 0;
  line-height: 20px;
  position: absolute;
  top: 4px;
  width: 27px;
}

.nem-1 {
  height: 20px;
  letter-spacing: 0;
  line-height: 20px;
  margin-bottom: 3px;
  margin-left: 7px;
  width: 45px;
}

.users-02-9 {
  height: 24px;
  margin-bottom: 1px;
  margin-left: 71px;
  width: 24px;
}

.overlap-group1-9 {
  align-items: center;
  background-size: 100% 100%;
  display: flex;
  height: 43px;
  margin-left: 2px;
  margin-top: 14px;
  min-width: 282px;
  padding: 6px 7px;
}

.overlap-group24 {
  height: 24px;
  margin-left: 7px;
  margin-top: 1px;
  position: relative;
  width: 140px;
}

.pancanke-swap-1 {
  height: 20px;
  left: 0;
  letter-spacing: 0;
  line-height: 20px;
  position: absolute;
  top: 1px;
  width: 122px;
}

.users-02-10 {
  height: 24px;
  left: 116px;
  position: absolute;
  top: 0;
  width: 24px;
}

.bnb-4 {
  height: 20px;
  letter-spacing: 0;
  line-height: 20px;
  margin-bottom: 3px;
  margin-left: 7px;
  width: 39px;
}

.users-02-11 {
  height: 24px;
  margin-left: 77px;
  margin-top: 1px;
  width: 24px;
}

.brain-trust-1 {
  height: 20px;
  letter-spacing: 0;
  line-height: 20px;
  margin-bottom: 1px;
  margin-left: 7px;
  width: 101px;
}

.users-02-12 {
  height: 24px;
  margin-bottom: 1px;
  margin-left: 15px;
  width: 24px;
}

.line-1-3 {
  height: 1001px;
  object-fit: cover;
  width: 1px;
}

.overlap-group-container {
  align-items: center;
  display: flex;
  flex-direction: column;
  margin-left: 64px;
  margin-top: 42px;
  min-height: 808px;
  width: 851px;
}

.overlap-group12-2 {
  align-items: flex-start;
  background-color: var(--mirage);
  border-radius: 20px;
  display: flex;
  gap: 53px;
  height: 54px;
  justify-content: flex-end;
  min-width: 851px;
  padding: 10px 14px;
}

.overlap-group27 {
  height: 33px;
  position: relative;
  width: 290px;
}

.total-invested-644350 {
  height: 33px;
  left: 0;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  top: 0;
  width: 290px;
}

.rupee-217 {
  height: 18px;
  left: 156px;
  position: absolute;
  top: 9px;
  width: 11px;
}

.total-profit-144350-312 {
  color: transparent;
  font-family: var(--font-family-taviraj);
  font-size: var(--font-size-xxxxl);
  font-weight: 600;
  height: 33px;
  letter-spacing: 0;
  line-height: normal;
  width: 301px;
}

.rank-20 {
  height: 33px;
  letter-spacing: 0;
  line-height: normal;
  width: 109px;
}

.overlap-group2-10 {
  height: 147px;
  margin-left: 0.09px;
  margin-top: 50px;
  position: relative;
  width: 791px;
}

.rectangle {
  background-color: var(--black);
  border: 0.5px solid;
  border-color: var(--dhancowhite);
  border-radius: 35px;
  height: 147px;
  left: 0;
  position: absolute;
  top: 0;
  width: 776px;
}

.line-28 {
  height: 117px;
  left: 162px;
  object-fit: cover;
  position: absolute;
  top: 15px;
  width: 1px;
}

.bitcoin-8 {
  height: 33px;
  left: 26px;
  letter-spacing: 0;
  line-height: 16px;
  position: absolute;
  text-align: center;
  top: 93px;
  width: 122px;
}

.total-invested-644350-1 {
  height: 44px;
  left: 192px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  top: 22px;
  width: 278px;
}

.quantity-bought-0032 {
  height: 44px;
  left: 507px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  top: 22px;
  width: 249px;
}

.current-value-806452 {
  height: 34px;
  left: 192px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  top: 83px;
  width: 300px;
}

.pl-5110022-312 {
  height: 34px;
  left: 507px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  top: 83px;
  transform: rotate(-0.16deg);
  width: 284px;
}

.rupee-218 {
  height: 18px;
  left: 325px;
  position: absolute;
  top: 36px;
  width: 11px;
}

.rupee-219 {
  height: 18px;
  left: 325px;
  position: absolute;
  top: 92px;
  width: 11px;
}

.rupee-220 {
  height: 19px;
  left: 552px;
  position: absolute;
  top: 94px;
  width: 11px;
}

.btc-9 {
  height: 70px;
  left: 45px;
  position: absolute;
  top: 16px;
  width: 70px;
}

.overlap-group-20 {
  height: 147px;
  margin-left: 0.09px;
  margin-top: 40px;
  position: relative;
  width: 791px;
}

.bnb-5 {
  -webkit-text-stroke: 3px var(--black);
  height: 33px;
  left: 17px;
  letter-spacing: 0;
  line-height: 16px;
  position: absolute;
  text-align: center;
  top: 91px;
  width: 122px;
}

.total-invested-644350-2 {
  height: 44px;
  left: 192px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  top: 16px;
  width: 278px;
}

.quantity-bought-42 {
  height: 44px;
  left: 507px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  top: 16px;
  width: 249px;
}

.current-value-806452-1 {
  height: 34px;
  left: 192px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  top: 77px;
  width: 300px;
}

.pl-5110022-312-1 {
  height: 34px;
  left: 507px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  top: 77px;
  transform: rotate(-0.16deg);
  width: 284px;
}

.rupee-221 {
  height: 18px;
  left: 325px;
  position: absolute;
  top: 30px;
  width: 11px;
}

.rupee-222 {
  height: 18px;
  left: 325px;
  position: absolute;
  top: 86px;
  width: 11px;
}

.rupee-223 {
  height: 19px;
  left: 552px;
  position: absolute;
  top: 88px;
  width: 11px;
}

.bnb-6 {
  height: 70px;
  left: 46px;
  position: absolute;
  top: 15px;
  width: 70px;
}

.etherum-3 {
  -webkit-text-stroke: 3px var(--black);
  height: 33px;
  left: 22px;
  letter-spacing: 0;
  line-height: 16px;
  position: absolute;
  text-align: center;
  top: 90px;
  width: 122px;
}

.total-invested-644350-3 {
  height: 44px;
  left: 192px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  top: 15px;
  width: 278px;
}

.quantity-bought-078 {
  height: 44px;
  left: 507px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  top: 15px;
  width: 249px;
}

.current-value-806452-2 {
  height: 34px;
  left: 192px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  top: 76px;
  width: 300px;
}

.pl-1110022-134 {
  height: 34px;
  left: 507px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  top: 76px;
  transform: rotate(-0.16deg);
  width: 284px;
}

.span0-2 {
  color: var(--wwwcoingeckocomred-orange);
  font-family: var(--font-family-taviraj);
  font-size: var(--font-size-xxl);
  font-weight: 600;
}

.span1-3 {
  color: var(--wwwcoingeckocomred-orange);
  font-family: var(--font-family-taviraj);
  font-size: var(--font-size-xxxxl);
  font-weight: 600;
}

.span5 {
  color: var(--wwwcoingeckocomred-orange);
  font-family: var(--font-family-taviraj);
  font-size: var(--font-size-s);
  font-weight: 600;
}

.rupee-224 {
  height: 18px;
  left: 325px;
  position: absolute;
  top: 29px;
  width: 11px;
}

.rupee-225 {
  height: 18px;
  left: 325px;
  position: absolute;
  top: 85px;
  width: 11px;
}

.rupee-226 {
  height: 19px;
  left: 552px;
  position: absolute;
  top: 87px;
  width: 11px;
}

.eth {
  height: 70px;
  left: 45px;
  position: absolute;
  top: 17px;
  width: 70px;
}

.overlap-group5-4 {
  height: 147px;
  margin-left: 0.09px;
  margin-top: 36px;
  position: relative;
  width: 791px;
}

.tether-4 {
  -webkit-text-stroke: 3px var(--black);
  height: 33px;
  left: 22px;
  letter-spacing: 0;
  line-height: 16px;
  position: absolute;
  text-align: center;
  top: 96px;
  width: 122px;
}

.total-invested-644350-4 {
  height: 44px;
  left: 192px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  top: 19px;
  width: 278px;
}

.quantity-bought-100 {
  height: 44px;
  left: 507px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  top: 19px;
  width: 249px;
}

.current-value-806452-3 {
  height: 34px;
  left: 192px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  top: 81px;
  width: 300px;
}

.pl-5110022-312-2 {
  height: 34px;
  left: 507px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  top: 81px;
  transform: rotate(-0.16deg);
  width: 284px;
}

.rupee-227 {
  height: 18px;
  left: 325px;
  position: absolute;
  top: 33px;
  width: 11px;
}

.rupee-228 {
  height: 18px;
  left: 325px;
  position: absolute;
  top: 90px;
  width: 11px;
}

.rupee-229 {
  height: 19px;
  left: 552px;
  position: absolute;
  top: 93px;
  width: 11px;
}

.usdt-1 {
  height: 70px;
  left: 45px;
  position: absolute;
  top: 20px;
  width: 70px;
}

.overlap-group10-4 {
  height: 998px;
  margin-left: 74px;
  margin-top: 1px;
  position: relative;
  width: 6px;
}

.rectangle-5205-1 {
  background-color: var(--mirage);
  border-radius: 10px;
  height: 671px;
  left: 0;
  position: absolute;
  top: 327px;
  width: 6px;
}

.rectangle-5206-1 {
  background-color: var(--dhancowhite);
  border-radius: 40px;
  height: 336px;
  left: 0;
  position: absolute;
  top: 0;
  width: 6px;
}
</style>
