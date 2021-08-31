<template>
  <footer class="text-center">
    <div class="footer-box d-flex">
      <div>
        <img class="logo" src="../../assets/logo.svg" />
      </div>
      <div class="footer-items" v-for="item in items" :key="item.id">
        <h5 class="title mb-5">{{ item.title }}</h5>
        <div class="d-flex links">
          <a
            class="mb-2"
            href="#"
            v-for="link in item.links"
            :key="link.id"
            >{{ link.text }}</a
          >
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  data() {
    return {
      items: [
        {
          id: "item1",
          title: "Product",
          links: [
            {
              id: "link1",
              text: "Overview",
            },
            {
              id: "link2",
              text: "Pricing",
            },
            {
              id: "link3",
              text: "Marketplace",
            },
            {
              id: "link4",
              text: "Features",
            },
            {
              id: "link5",
              text: "Integrations",
            },
          ],
        },
        {
          id: "item2",
          title: "Company",
          links: [
            {
              id: "link1",
              text: "About",
            },
            {
              id: "link2",
              text: "Team",
            },
            {
              id: "link3",
              text: "Blog",
            },
            {
              id: "link4",
              text: "Careers",
            },
          ],
        },
        {
          id: "item1",
          title: "Connect",
          links: [
            {
              id: "link1",
              text: "Contact",
            },
            {
              id: "link2",
              text: "Newsletter",
            },
            {
              id: "link3",
              text: "LinkedIn",
            },
          ],
        },
      ],
    };
  },
};
</script>

<style scoped>
footer {
  background-color: hsl(240, 10%, 16%);
  border-top-right-radius: 80px;
  position: relative;
  height: 50rem;
  overflow: hidden;
  color: white;
  /* margin-bottom: 8rem; */
  padding: 4rem;
}

.footer-box {
  justify-content: space-evenly;
  position: relative;
  right: 4rem;
}
.title {
  text-align: left;
}
.links {
  flex-direction: column;
}
.links a {
  color: hsl(240, 2%, 79%);
  text-align: left;
}

@media screen and (max-width: 767.5px) {
  footer {
    height: 70rem;
    padding: 3rem;
  }
  .footer-items {
    margin-bottom: 2rem;
  }
  .footer-box {
    flex-direction: column;
    position: relative;
    right: 0rem;
  }
  .title {
    text-align: center;
    font-size: 1.5rem;
  }
  .links a {
    color: hsl(240, 2%, 79%);
    text-align: center;
    font-size: 1.2rem;
  }
  .logo {
    margin-bottom: 4rem;
  }
}
</style>