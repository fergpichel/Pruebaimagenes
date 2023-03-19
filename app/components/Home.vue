<template>
    <Page>
        <ActionBar>
            <Label text="Prueba chunga 7"/>
        </ActionBar>
        <ScrollView>
              <StackLayout>
                  <Label text="Imagen 1" />
                  <Image src="~/assets/00prueba"/>

                  <Label text="Imagen 2" />
                  <Image src="~/01Longitud"/>

                  <Label text="Imagen 3" />
                  <Image src="@/assets/00prueba.png"/>

                  <Label text="Imagen 4" />
                  <Image src="~/assets/01Longitud.png" stretch="none" />

                  <Label text="Imagen 5" />
                  <Image src="~/assets/01Longitud" stretch="none" />
                  <Button text="Botón" @tap="onButtonTap" />

                  <Label text="Imagen 6" />
                  <Image src="~/assets/01Longitud.png" stretch="none" />

                  <Label text="Imagen 7" />
                  <Image src="~/assets/00prueba.png" stretch="none" />

                  <Label text="Imagen 8" />
                  <Image src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/99/Unofficial_JavaScript_logo_2.svg/1200px-Unofficial_JavaScript_logo_2.svg.png" />

                  <Label text="Imagen 9" />
                  <Image src="~/assets/00prueba.png" stretch="none" />

                  <Label text="Imagen 10" />
                  <Image src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/99/Unofficial_JavaScript_logo_2.svg/1200px-Unofficial_JavaScript_logo_2.svg.png" stretch="none" />
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
