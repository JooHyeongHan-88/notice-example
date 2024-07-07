<script>
    import Card from "./Card.svelte";
</script>

<div class="container mt-5">
    <h1>테스트</h1>
    <div class="section">
        <div class="wrapper">
            <Card />
            <Card />
            <Card />
            <Card />
            <Card />
            <Card />
            <Card />
        </div>
    </div>
</div>

<style>
    .section {
        display: flex;
        justify-content: center;
    }
    .wrapper {
        display: flex;
        flex-wrap: wrap;
        gap: 25px; /* 카드 간의 간격을 고정 */
        align-items: flex-start; /* 마지막 줄 카드가 왼쪽 정렬되도록 설정 */
        max-width: 100%;
    }
</style>