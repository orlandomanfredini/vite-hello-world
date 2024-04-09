<script>
export default {
    data(){
        return{
            currentIndex: 0,
            links: [
            'https://www.google.com/search?q=boolean&rlz=1C5CHFA_enIT999IT999&oq=boo&gs_lcrp=EgZjaHJvbWUqDAgCECMYJxiABBiKBTIGCAAQRRg5MgwIARAjGCcYgAQYigUyDAgCECMYJxiABBiKBTIMCAMQABhDGIAEGIoFMgwIBBAAGEMYgAQYigUyEggFEAAYQxiDARixAxiABBiKBTIMCAYQABhDGIAEGIoFMg0IBxAAGIMBGLEDGIAEMgcICBAAGI8CMgcICRAAGI8C0gEJNTkwOWowajE1qAIAsAIA&sourceid=chrome&ie=UTF-8',
            'https://www.google.com/search?q=boolean&rlz=1C5CHFA_enIT999IT999&oq=boo&gs_lcrp=EgZjaHJvbWUqDAgCECMYJxiABBiKBTIGCAAQRRg5MgwIARAjGCcYgAQYigUyDAgCECMYJxiABBiKBTIMCAMQABhDGIAEGIoFMgwIBBAAGEMYgAQYigUyEggFEAAYQxiDARixAxiABBiKBTIMCAYQABhDGIAEGIoFMg0IBxAAGIMBGLEDGIAEMgcICBAAGI8CMgcICRAAGI8C0gEJNTkwOWowajE1qAIAsAIA&sourceid=chrome&ie=UTF-8',
            'https://www.google.com/search?q=boolean&rlz=1C5CHFA_enIT999IT999&oq=boo&gs_lcrp=EgZjaHJvbWUqDAgCECMYJxiABBiKBTIGCAAQRRg5MgwIARAjGCcYgAQYigUyDAgCECMYJxiABBiKBTIMCAMQABhDGIAEGIoFMgwIBBAAGEMYgAQYigUyEggFEAAYQxiDARixAxiABBiKBTIMCAYQABhDGIAEGIoFMg0IBxAAGIMBGLEDGIAEMgcICBAAGI8CMgcICRAAGI8C0gEJNTkwOWowajE1qAIAsAIA&sourceid=chrome&ie=UTF-8',
            'https://www.google.com/search?q=boolean&rlz=1C5CHFA_enIT999IT999&oq=boo&gs_lcrp=EgZjaHJvbWUqDAgCECMYJxiABBiKBTIGCAAQRRg5MgwIARAjGCcYgAQYigUyDAgCECMYJxiABBiKBTIMCAMQABhDGIAEGIoFMgwIBBAAGEMYgAQYigUyEggFEAAYQxiDARixAxiABBiKBTIMCAYQABhDGIAEGIoFMg0IBxAAGIMBGLEDGIAEMgcICBAAGI8CMgcICRAAGI8C0gEJNTkwOWowajE1qAIAsAIA&sourceid=chrome&ie=UTF-8',

            ]
        }
    }
}
</script>

<template>
    
        <ul>
            <li v-for="link in links"><a :href="link">Link</a></li>
        </ul>
    
</template>

<style scoped>
ul, li, menu{
    list-style: none;
}

ul{
    display: flex;
    align-items: center;
    justify-content: space-around;
    gap: 5px;
    margin: 0;
    padding: 0;
}


a{
    color: black;
    text-decoration: none;
    font-size: 13px;
}
</style>