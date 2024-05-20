<template>
    <main>
        <div class="container">
            <div class="borda-login">
                <div class="login">
                    <label class="name">Nome:</label>
                    <input type="name" class="searchname" placeholder="Nome"><br>
                    <label class="email">Email:</label>
                    <input type="email" class="searchemail" placeholder="Digite seu email..."><br>
                    <label for="input" class="senha">Password:</label>
                    <input type="password" class="searchsenha" placeholder="Digite a sua senha...">
                    <br>
                    <router-link aria-current="page" to="/login">
                        <button type="button" class="btn-login">Cadastrar</button>
                    </router-link>
                </div>
            </div>
        </div>
    </main>
</template>


<style>
.container {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 75vh;
}

.center {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100%;
}

.borda-login {
    border: 2px solid black;
    border-radius: 5px;
    padding: 20px;
    width: 300px;
    background-color: #ffffff;
    box-shadow: 0px 0px 10px 0px rgba(0,0,0,0.1);
}

.login {
    text-align: center;
    margin-bottom: 10px;
}

.email, .senha {
    display: block;
    margin-bottom: 5px;
    color: #333333;
}

.searchname, .searchsenha {
    width: 100%;
    padding: 10px;
    margin-bottom: 10px;
    border: 1px solid #ccc;
    border-radius: 4px;
    box-sizing: border-box;
}

.searchemail, .searchsenha {
    width: 100%;
    padding: 10px;
    margin-bottom: 10px;
    border: 1px solid #ccc;
    border-radius: 4px;
    box-sizing: border-box;
}


.btn-login {
    margin-top: 10px;
    padding: 5px 10px;
    background-color: #007bff;
    color: #fff;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    width: 100%;
    transition: background-color 0.3s;
}

.btn-login:hover {
    background-color: #0056b3;
}
</style>
