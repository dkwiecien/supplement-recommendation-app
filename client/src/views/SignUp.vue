<script setup lang="ts"></script>

<template>
    <div class="min-h-screen flex justify-center">
        <div class="border h-100 rounded-lg flex flex-col items-center justify-center px-20 py-10 mt-14">
            <h1 class="text-2xl font-bold mb-10">Sign up</h1>
            <div class="mb-3">
                <label for="formGroupExampleInput" class="form-label">Username</label>
                <input type="text" class="form-control" id="formGroupExampleInput" placeholder="username">
            </div>
            <div class="mb-3">
                <label for="formGroupExampleInput2" class="form-label">Email</label>
                <input type="text" class="form-control" id="formGroupExampleInput2" placeholder="email@email.com">
            </div>
            <div class="mb-3">
                <label for="formGroupExampleInput2" class="form-label">Password</label>
                <input type="text" class="form-control" id="formGroupExampleInput2" placeholder="********">
            </div>
            <button type="button" class="btn btn-outline-light my-4">Submit</button>
        </div>
    </div>
</template>