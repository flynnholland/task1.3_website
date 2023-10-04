<template>
    <div>
        <h1>Contact Me</h1>
        <form @submit.prevent="submitForm">
            <label for="name">Name:</label>
            <input type="text" id="name" v-model="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" v-model="email" required>
            <label for="subject">Subject:</label>
            <input type="text" id="subject" v-model="subject" required>
            <label for="message">Message:</label>
            <textarea id="message" v-model="message" required></textarea>
            <button type="submit">Send</button>
        </form>
    </div>
</template>

<script>
</script>