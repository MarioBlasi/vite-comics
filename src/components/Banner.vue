<script>
export default {
  data() {
    return {
      banner: [
        {
          text: "Digita Comics",
          src: "buy-comics-digital-comics.png",
        },
      ],
    };
  },
  methods: {
    getImageUrl(name) {
      return new URL(`./assets/img/${name}.png`, import.meta.url).href;
    },
  },
};
</script>
