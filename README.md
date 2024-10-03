# AliExpress Counterpart

### Fullstack application
(AliExpress clone)

<h3 align="left">Languages and Tools:</h3>
<p align="left"> 
    <a href="https://vuejs.org/" target="_blank" rel="noreferrer"> 
        <img src="https://cdn.iconscout.com/icon/free/png-256/free-vue-logo-icon-download-in-svg-png-gif-file-formats--company-brand-world-logos-vol-5-pack-icons-282497.png?f=webp&w=256" alt="VueJs" width="40" height="40"/> 
    </a>
    <a href="https://nuxt.com/" target="_blank" rel="noreferrer"> 
        <img src="https://seeklogo.com/images/N/nuxt-logo-5EF50E1ABD-seeklogo.com.png" alt="Nuxt" width="40" height="40"/> 
    </a> 
    <a href="https://tailwindui.com/" target="_blank" rel="noreferrer"> 
        <img src="https://upload.wikimedia.org/wikipedia/commons/d/d5/Tailwind_CSS_Logo.svg" alt="tailwindui" width="40" height="40"/> 
    </a> 
    <a href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer"> 
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="40" height="40"/>
    </a> 
    <a href="https://www.prisma.io/" target="_blank" rel="noreferrer"> 
        <img src="https://i.pinimg.com/originals/39/b2/e4/39b2e4ad77c23a2c11e5950a7dfa2aec.png" alt="prisma" width="40" height="40"/>
    </a>  
    <a href="https://supabase.com/" target="_blank" rel="noreferrer"> 
        <img src="https://seeklogo.com/images/S/supabase-logo-DCC676FFE2-seeklogo.com.png" alt="supabase" width="40" height="40"/>
    </a> 
    <a href="https://stripe.com/" target="_blank" rel="noreferrer"> 
        <img src="https://freelogopng.com/images/all_img/1685814267stripe-logo-png.png" alt="stripe" width="40" height="40"/>
    </a> 
</p>

## App Setup (localhost)

```
git clone https://github.com/Gorgona9/aliexpress-counterpart.git

cp .env.example .env

npm i

npx prisma generate

npm run dev
```

You'll have to setup a Supabase account & Stripe account, then add all the details into your .env file.

Once you've connected your application to Supabase. You'll also need to setup the Auth Providers:
Google [Google](https://cloud.google.com)
Github [Github](https://github.com/settings/developers)

    https://supabase.com/docs/guides/auth/social-login/auth-google
    https://supabase.com/docs/guides/auth/social-login/auth-github

Now run the command to migrate your database tables and run your seed file.

```
npx prisma migrate dev --name init
```

You should be good to go! If you need any more help, take a look at the tutorial video by clicking the image above.

# Application Images

<img width="1439" src="/public/presentation/1.png">
<img width="1439" src="/public/presentation/2.png">
<img width="1439" src="/public/presentation/3.png">
<img width="1439" src="/public/presentation/4.png">
<img width="1439" src="/public/presentation/5.png">
<img width="1439" src="/public/presentation/6.png">
<img width="1439" src="/public/presentation/7.png">
