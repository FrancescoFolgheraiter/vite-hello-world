<script>
export default {
    data() {
        return { text:"Questo è il mio header"}
    }
};
</script>

<template>
    <div>
        <header>
            <h2>{{text}}</h2>
            <nav>
              <ul>
                <li>
                  <a href="">
                    Menu 1
                  </a>
                </li>
                <li>
                  <a href="">
                    Menu 2
                  </a>
                </li>
                <li>
                  <a href="">
                    Menu 3
                  </a>
                </li>
                <li>
                  <a href="">
                    Menu 4
                  </a>
                </li>
              </ul>
            </nav>
        </header>
    </div>
</template>

<style scoped>
  header{
    background-color: lightskyblue;
    border: 1px solid brown;
    max-width: 1200px;
    margin:20px auto;
    padding: 20px;
    text-align: center;
  }
  ul{
    list-style: none;
    padding:0;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
  }
</style>
