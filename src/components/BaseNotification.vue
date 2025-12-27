<template>
    <div class = "notification__container">
        <div class="notification__icon">
            <img src="@/components/Group105.png" alt="Group105.png">
        </div>
        <div class="notification__text">
            <h4>Someting wrong</h4>
            <p>Lorem ipsum dolor sit amet</p>
        </div>
    </div>
</template>

<script>
export default {
  name: 'BaseNotification',
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

.notification__container {
    width: 408px;
    height: 73px;
    background: #FFFFFF;
    border: 1px solid #F85640;
    border-radius: 8px;
    display: flex;
    align-items: center;
}

img {
    width: 28px;
    height: 28px;
    margin: 20px;
}

.notification__text h4 {
    font-family: 'Poppins', sans-serif;
    font-weight: 600;
    font-size: 16px;
    line-height: 20px;
    color: #F85640;
    margin-bottom: 4px;
}

.notification__text p {
    font-family: 'Poppins', sans-serif;
    font-weight: 400;
    font-size: 11px;
    line-height: 18px;
    color: #79170A;
    letter-spacing: 0.5px;
    }

</style>