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
    <div class="col-6">
        <ul>
            <li v-for="link in links"><a :href="link"></a></li>
        </ul>
    </div>
</template>

<style></style>