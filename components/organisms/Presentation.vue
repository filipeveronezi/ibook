<template>
  <div class="presentation">
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Eligendi
      necessitatibus maxime, id voluptatibus incidunt perferendis repellat
      expedita quos cumque quia modi qui quae, deserunt dolorum eos aspernatur
      facere, provident atque! Voluptatibus, optio! Vero nihil culpa
      consequuntur eius quasi nobis veniam molestias id quas tempore, obcaecati
      commodi, natus quam itaque error. Nesciunt voluptatem quaerat dicta
      aspernatur maiores exercitationem reiciendis. Eveniet, porro. Veritatis
      tempora veniam doloremque quia quis voluptas laudantium officia voluptate
      provident repellat quas vel magni sapiente, repudiandae molestias
      aspernatur? Sit natus consectetur dolores facere perspiciatis iusto
      veritatis perferendis ea impedit.
    </p>
    <img src="@/assets/img/presentation.svg" alt="Apresentação do iBook" />
  </div>
</template>

<style lang="scss" scoped>
.presentation {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-gap: 2rem;
  align-items: center;
  @include screen('small', 'medium') {
    grid-template-columns: 1fr;
  }
  p {
    line-height: 26px;
  }
  img {
    max-width: 100%;
  }
}
</style>
