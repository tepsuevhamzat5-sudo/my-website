# avtoinstruktor_zali

Статический сайт (один index.html, без сборки).

## Публикация на Vercel
1. Через сайт: vercel.com -> Add New -> Project -> загрузите папку (или подключите GitHub-репозиторий). Framework Preset: Other. Build Command и Output Directory оставьте пустыми.
2. Через CLI: `npm i -g vercel`, затем `vercel --prod` в этой папке.

## Свой домен
Project -> Settings -> Domains -> добавьте avtoinstruktor-zali.ru и внесите у регистратора DNS-записи, которые покажет Vercel (A 76.76.21.21 для корня, CNAME cname.vercel-dns.com для www).
