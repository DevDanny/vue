<template>
    <div class="calculator">
        <div class="display">
            0.0522348
        </div>
        <div class="btn">c</div>
        <div class="btn">+/-</div>
        <div class="btn">%</div>
        <div class="btn">/</div>
        <div class="btn">7</div>
        <div class="btn">8</div>
        <div class="btn">9</div>
        <div class="btn">x</div>
        <div class="btn">4</div>
        <div class="btn">5</div>
        <div class="btn">6</div>
        <div class="btn">-</div>
        <div class="btn">1</div>
        <div class="btn">2</div>
        <div class="btn">3</div>
        <div class="btn">+</div>
        <div class="btn zero">0</div>
        <div class="btn">.</div>
        <div class="btn">=</div>
    </div>
</template>

<style lang="stylus" scoped>
.calculator{
    font-size: 40px;
    display: grid;
    grid-grid-template-columns : repeat(4, 1fr);
    grid-grid-auto-rows: minmax(50px, auto);

}

.display{
    grid-column: 1/5;
}
.zero{
    grid-column: 1 / 3;
}
.btn{
    background: #eee;
    border: 1px solid black ;
}

</style>

<script>
export default {
    name: 'app'
}
</script>