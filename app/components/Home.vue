<template>
    <Page>
        <ActionBar>
            <Label text="Prueba chunga"/>
        </ActionBar>
        <ScrollView>
              <StackLayout>
                  <Label text="Esto no va 01" />
                  <Image src="app/assets/00prueba.png"/>
                  <Image src="~/assets/01Longitud.png" stretch="none" />
                  <Button text="Botón" @tap="onButtonTap" />

                  <Image src="~/assets/01Longitud.png" stretch="none" />
                  <Image src="~/assets/00prueba.png" stretch="none" />
                  <Image src="https://i.etsystatic.com/6792824/r/il/4cd9bd/4246801182/il_794xN.4246801182_d2z8.jpg" />
                  <Label text="Esto no va 02" />
                  <Image src="~/assets/00prueba.png" stretch="none" />
                  <Image src="https://i.etsystatic.com/6792824/r/il/4cd9bd/4246801182/il_794xN.4246801182_d2z8.jpg" stretch="none" />
              </StackLayout>
        </ScrollView>
    </Page>
</template>

<script>
  export default {
    computed: {
      message() {
        return "Blank {N}-Vue app";
      }
    }
  };
</script>

<style scoped lang="scss">
    //@import '@nativescript/theme/scss/variables/blue';

    // Custom styles
    //.fas {
       // @include colorize($color: accent);
    //}

    //.info {
        //font-size: 20;
        //horizontal-align: center;
        //vertical-align: center;
    //}
</style>
