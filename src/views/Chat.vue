<template>
    <div>
        <h1>ちゃっと</h1>
        <div class="chatlayout">
        </div>
        <div class="inputlayoutoutter">
            <input type="text">
            <button>✈</button>
        </div>
    </div>
</template>

<style scoped>
.chatlayout {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    height: 50vh;
}

.inputlayoutoutter {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 4vh;
    background-color: #f0f0f0;
    border-radius: 20px;
    padding: 0 70px 0 20px;
    margin: 0 30px 0 20px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
}

input {
    background-color: #f0f0f0;
    border: none;
    height: 30px;
    width: 100%;
    cursor: text;
}

input[type="text"]:focus {
  border: none;
  outline: 0;
}
</style>