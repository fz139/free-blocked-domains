# Blocked but expired domains

A collection of expired domains previously blocked by Russia's Roskomnadzor, now available for free registration. Reclaim the web! 🌐🔓

## How it assembles?

* First, we've get a list of resourses blocked by Roskomnadzor from secret sources.
* Then, we've get A and AAAA records (or NXDOMAIN answer) for each domain by this tool: https://github.com/fz139/vigruzki-dns-resolver
* Then, we've filtered out domains with NXDOMAIN answer using mozilla public suffix list and test for expiration by this tool: https://github.com/fz139/available-domain-finder

It is not rocket science, but it works. All this tools are written in free time. 

## What reason for this list?

A partialy control of Roskomnadzor blocking system was in your hands if you can control blocking domain. You could attack arbitrary host by putting it in the blocked domain A record. Now Russia blocking system uses smart technologies so this technique is not so effective as it was before. But it still works. Possibly.

However the histroty if this technique is very impressive:
* [Series of "DNS attacks" in 2017](https://usher2.club/articles/dns-attack-2017/) :ru:
* [Collapse of TTK on March 14, 2018](https://usher2.club/articles/ttk-strike/) :ru:
* [Registry of free ads 149-FZ.801](https://usher2.club/articles/msg-digitalresistance/) :ru:

We sure that thos history must be public. So we've decided to publish this archive.

# Заблокированные истекшие домены

Коллекция доменов, ранее заблокированных Роскомнадзором, теперь доступных для свободной регистрации. Верните себе интернет! 🌐🔓

## Как это собирается?

* Сначала мы получаем список ресурсов, заблокированных Роскомнадзором, из секретных источников.
* Затем мы получаем записи A и AAAA (или ответ NXDOMAIN) для каждого домена с помощью этого инструмента: https://github.com/fz139/vigruzki-dns-resolver
* Затем мы фильтруем домены с ответом NXDOMAIN, используя список публичных суффиксов mozilla и проверяем срок действия с помощью этого инструмента: https://github.com/fz139/available-domain-finder

Это не ракет сайнс, но это работает. Все эти инструменты написаны в свободное время. 

## Какая цель этого списка?

Частичный контроль над системой блокировки Роскомнадзора был в ваших руках, если вы могли контролировать блокирующий домен. Вы могли атаковать произвольный хост, поместив его в запись A заблокированного домена. Теперь система блокировки России использует умные технологии, поэтому эта техника не так эффективна, как раньше. Но это все еще работает. Возможно.

Однако история этой техники очень впечатляет:
* [Серия "DNS-атак" в 2017 году](https://usher2.club/articles/dns-attack-2017/)
* [Падение ТТК 14 марта 2018 года](https://usher2.club/articles/ttk-strike/)
* [Реестр бесплатных объявлений 149-ФЗ.801](https://usher2.club/articles/msg-digitalresistance/)

Мы уверены, что эта история должна быть общедоступной. Поэтому мы решили опубликовать этот архив.
