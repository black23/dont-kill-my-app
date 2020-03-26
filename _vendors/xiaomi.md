---
name: Xiaomi
subtitle: except Android One
manufacturer:
  - xiaomi
position: 4
award: 4
redirect_from: /vendors/xiaomi.html
explanation: "
Xiaomi a jejich nadstavba Android s názvem MIUI je vyhlášená nestandardním přístupem k běhu aplikací na pozadí a systémovým právům. Pro tuto nadstavbu neexistuje žádné API ani dokumentace. 
Ve výchozím nastavení telefonu procesy na pozadí často nefungují správně a aplikace, které je využívají také ne.


> POZOR: Zařízení od Xiaomi s Android One pracují výrazně lépe, než zařízení s MIUI. Takže pokud se vám líbí Xiaomi, doporučujeme se poohlédnout po zařízeních s podporou Android One.
"

user_solution: '

### MIUI 10

Aby mohla aplikace běžela úspěšně na pozadí zkontrolujte, že nastavení vypadají jako na následujících obrázcích (je na nich příklad s aplikaci Sleep as Android):


<div class="img-block">
  <img src="/assets/img/ss_xiaomi_1a.png">
  <img src="/assets/img/ss_xiaomi_1b.png">
  <img src="/assets/img/ss_xiaomi_1c.png">
</div>


### Správa napájení


Prosím zapněte:

* *Nastavení (Settings) > Rozšíření nastavení (Advanced Settings) > Správce baterie (Battery manager) > Režim (Power plan)* nastavte na Výkon (Performance)

* *Nastavení zařízení (Device Settings) > Pokročilé nastavené (Advanced Settings) > Správce baterie (Battery Manager) > Chráněné aplikace (Protected apps)* – aplikace musí být označena jako chráněná (Protected)

* *Nastavení zařízení (Device Settings) > Aplikace (Apps) > aplikace > Baterie (Battery) > Náročná na napájení (Power-intensive)* a *Nechat běžet po zhasnutí displeje (Keep running after screen off)*

* *Nastavení (Settings) > Additional Settings > Battery & Performance > Manage apps’ battery usage* and here:

1. Přepněte Úsporné režimy (Power Saving Modes) do stavu vypnuto 

2. Choose the next options: *Saving Power in The Background > Choose apps > select your app > Background Settings > No restrictions*


### Šetření baterie (App battery saver)

*Zabezpečení (Security) > Baterie (Battery) > Šteření batereie (App Battery Saver) > název aplikace  > Bez omezení (No restriction)*


### Zapnutí automatického spuštění aplikace

(podle článku [Xiaomi](https://in.c.mi.com/thread-253478-1-0.html):

V sekci *Zabezpečení (Security) > Oprávnění (Permissions) > Automatické spouštění (Auto-start)*

<div class="img-block">
  <img src="/assets/img/ss_xiaomi_as_1.png">
  <img src="/assets/img/ss_xiaomi_as_2.png">
    <div class="img-block">
     <figure>
          <img src="/assets/img/ss_xiaomi_as_3.png">
       <figcaption>Vyhledejte aplikaci a ťuknutím aktivujte</figcaption>
     </figure>
    </div>
</div>    

### Připnutí aplikace (App pinning)

Pokud otevřete seznam nedávno spuštěných aplikací a přetáhnete vybranou aplikaci dolů, dojde k jejímu připnutí. Zůstane spuštěna i pokud vymažete seznam nedávno spuštěných aplikací. Pokud aplikaci chcete odepnout, opět ji přetáhněte směrem dolů.


'

developer_solution: "V současné chvíli nevíme o žádném řešení pro vývojáře."
---
