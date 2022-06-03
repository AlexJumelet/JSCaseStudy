<template>
  <v-app>
    <v-main>
      <v-container>
        <v-row>
          <v-col>
            <HeaderShape class="HeaderShape"></HeaderShape>
            <HeaderShape class="BottomHeaderShape"></HeaderShape>
          </v-col>
        </v-row>
      </v-container>
      <v-container>
        <Title>Overzicht van je rewards</Title>
        Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy
        eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam
        voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet
        clita kasd gubergren, no sea takimata sanctus.
        <v-row>
          <v-col :sm="12" style="max-width: 285px">
            <FeaturedCard>
              <FeaturedCardTop>
                <div>Persoonlijke Punten</div>
                <FeaturedCardStat>32</FeaturedCardStat>
              </FeaturedCardTop>
              <v-row>
                <v-col>
                  <v-card-text>
                    Behaalde punten
                    </v-card-text>
                </v-col>
              </v-row>
              <v-container>
                <v-row>
                  <v-col>
                    <FeatureCardTextBox class="FeatureCardTextBox"> van tot</FeatureCardTextBox>
                  </v-col>
                </v-row>
              </v-container>
              <v-container>
                <v-row>
                  <v-col :md="3"> 
                    <Badge>5</Badge>
                  </v-col>
                    <v-col align-items="left">
                      Inloggen
                    </v-col>
                </v-row>
                <v-row>
                  <v-col :md="3">
                    <Badge>5</Badge>
                  </v-col>
                  <v-col align-self="left">
                      Profiel
                  </v-col>
                </v-row>
                <v-row>
                  <v-col :md="3">
                    <Badge>1</Badge>
                  </v-col>
                  <v-col align-self="left">
                      Comment
                  </v-col>
                </v-row>                
              </v-container>
            </FeaturedCard>
          </v-col>
          <v-col :cols="12" md="auto grow">
            <v-card> Behaalde Badges </v-card>
            <div>Omschrijving: Hier staat text</div>
            <v-row>
              <v-col :sm="6" md="8" style="max-width: 285px">
                <ContentCard>
                  <CardImageTop class="imglocked">
                    <div class="CardImageTop__img"></div>
                  </CardImageTop>
                  <ContentCardStat></ContentCardStat>
                  <BadgeImage class="locked">
                    <div class="BadgeImage__img"></div>
                  </BadgeImage>
                  <v-card-text class="TextStyleBadge">
                    <div class="TextStyle1">
                      Leeractiviteiten                       
                      </div>
                      </v-card-text>
                    <v-card-text class="TextStyleBadge">
                      <div class="TextStyle2">
                        Je hebt 2 van de 5 leeractiviteiten afgerond. Rond er 5 af en verdien de bronze badge
                      </div>
                      </v-card-text>
                </ContentCard>
                <ContentCardBottom> </ContentCardBottom>
              </v-col>
              <v-col :sm="6" md="8" style="max-width: 285px">
                <ContentCard>
                  <CardImageTop class="imgbronze">
                    <div class="CardImageTop__img"></div>
                  </CardImageTop>
                  <ContentCardStat></ContentCardStat>
                  <BadgeImage class="bronze">
                    <div class="BadgeImage__img"></div>
                  </BadgeImage>
                   <v-card-text class="TextStyleBadge">
                    <div class="TextStyle1">
                      Leeractiviteiten                       
                      </div>
                      </v-card-text>
                    <v-card-text class="TextStyleBadge">
                      <div class="TextStyle2">
                        Je hebt 2 van de 5 leeractiviteiten afgerond. Rond er 5 af en verdien de bronze badge
                      </div>
                      </v-card-text>
                </ContentCard>
                <ContentCardBottom> </ContentCardBottom>
              </v-col>
              <v-col :sm="6" :md="8" style="max-width: 285px">
                <ContentCard>
					          <CardImageTop class="imgpurple">
                    	<div class="CardImageTop__img"></div>
                  	</CardImageTop>
                  <ContentCardStat></ContentCardStat>
                  <BadgeImage class="bpurple">
                    <div class="BadgeImage__img"></div>
                  </BadgeImage>
                  <v-card-text class="TextStyleBadge">
                    <div class="TextStyle1">
                      Leeractiviteiten                       
                      </div>
                      </v-card-text>
                    <v-card-text class="TextStyleBadge">
                      <div class="TextStyle2">
                        Je hebt 2 van de 5 leeractiviteiten afgerond. Rond er 5 af en verdien de bronze badge
                      </div>
                      </v-card-text>
                </ContentCard>
                <ContentCardBottom> </ContentCardBottom>
              </v-col>
            </v-row>
            <v-row>
				<v-col :sm="6" :md="8" style="max-width: 285px">
					<ContentCard>
						<CardImageTop class="imggold">
							<div class="CardImageTop__img"></div>
						</CardImageTop>
						<ContentCardStat></ContentCardStat>
						<BadgeImage class="gold">
							<div class="BadgeImage__img"></div>
							</BadgeImage>
						    <v-card-text class="TextStyleBadge">
                <div class="TextStyle1">
                  Leeractiviteiten                       
                </div>
                  </v-card-text>
                    <v-card-text class="TextStyleBadge">
                      <div class="TextStyle2">
                        Je hebt 2 van de 5 leeractiviteiten afgerond. Rond er 5 af en verdien de bronze badge
                      </div>
                    </v-card-text>
					</ContentCard>
          <ContentCardBottom></ContentCardBottom>
				</v-col>
					<v-col :sm="6" :md="8" style="max-width: 285px">
					<ContentCard>
						<CardImageTop class="plat">
							<div class="CardImageTop__img"></div>
						</CardImageTop>
						<ContentCardStat></ContentCardStat>
						<BadgeImage class="plat">
							<div class="BadgeImage__img"></div>
							</BadgeImage>
						                  <v-card-text class="TextStyleBadge">
                    <div class="TextStyle1">
                      Leeractiviteiten                       
                      </div>
                      </v-card-text>
                    <v-card-text class="TextStyleBadge">
                      <div class="TextStyle2">
                        Je hebt 2 van de 5 leeractiviteiten afgerond. Rond er 5 af en verdien de bronze badge
                      </div>
                      </v-card-text>
					</ContentCard>
          <ContentCardBottom></ContentCardBottom>
				</v-col>	
				 </v-row>
          </v-col>
        </v-row>
      </v-container>
    </v-main>
  </v-app>
</template>