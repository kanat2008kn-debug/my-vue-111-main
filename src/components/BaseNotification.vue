<template>
    <div class = "notification">
        <div class="notification__icon">
            <img src="@/components/Group105.png" alt="Group105.png">
        </div>
        <div class="notification__text">
            <h4>{{ title }}</h4>
            <p>{{ text }}</p>
        </div>
    </div>
</template>

<script>
export default {
  name: 'BaseNotification',
    data() {
        return {
            title: 'Someting wrong',
            text: 'Lorem ipsum dolor sit amet',
        };
    },
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

.notification {
    width: 408px;
    height: 73px;
    background: #FFFFFF;
    border: 1px solid #F85640;
    border-radius: 8px;
    display: flex;
    align-items: center;
    margin: 20px;
}

.notification--danger {
        background-color: #FFF8F8;
        border: 1px solid #F85640;
    }

    .notification--warning {
        background-color: #FFF8EF;
        border: 1px solid #FBA63C;
    }

    .notification--success {
        background-color: #DCF3EB;
        border: 1px solid #34A770;
    }

    .notification--info {
        background-color: #E1F2FC;
        border: 1px solid #08A0F7;
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

.notification--danger h3 {
        color: #F85640;
    }

    .notification--danger p {
        color: #79170A;
    }

    .notification--warning h3 {
        color: #E18109;
    }

    .notification--warning p {
        color: #BC741A;
    }

    .notification--success h3 {
        color: #13854E;
    }

    .notification--success p {
        color: #10673E;
    }

    .notification--info h3 {
        color: #08A0F7;
    }

    .notification--info p {
        color: #3387B7;
    }

</style>