<div align="center">

<img src="assets/header.svg" width="100%" alt="Arthur Avagyan — Software Engineering Student · C · Linux · Python" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/arthavagyan)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:arthavagy@gmail.com)
[![CV](https://img.shields.io/badge/CV-4285F4?style=for-the-badge&logo=googledrive&logoColor=white)](https://drive.google.com/file/d/1Wg4sBJCw-wbwnl68sQes4tj4FEUyJxB6/view?usp=sharing)
![Yerevan](https://img.shields.io/badge/Yerevan,_Armenia-0d1117?style=for-the-badge&logo=googlemaps&logoColor=7ce0ff)

</div>

## `$ cat arthur.h`

```c
typedef struct s_engineer
{
    char    *name;        // "Arthur Avagyan"
    char    *based_in;    // "Yerevan, Armenia"
    char    *studying[2]; // NPUA — Applied Math & Informatics (final year)
                          // 42 Yerevan — Software Engineering
    char    *working_at;  // TUMO Center for Creative Technologies
    char    *core[3];     // { "C", "Python", "Bash" }  on  Linux/Unix
    char    *into;        // algorithms, memory management, low-level systems
    int     memory_leaks; // 0 — checked with valgrind, every time
}   t_engineer;
```

I'm a final-year Applied Mathematics & Informatics student at **NPUA**, and at the same time I'm training as a software engineer at **42 Yerevan**. 42's peer-to-peer model taught me to learn on my own, read other people's code, and debug without a teacher. At **TUMO** I built an automated schedule-display system that now runs the center's information screens. I also teach C and Linux to other students, because explaining something is the best test of whether you understand it.

## `$ ls ~/experience`

| | Role | Where | When |
|:-:|:--|:--|:--|
| 🖥️ | **Information Desk Coordinator** <br/><sub>Student & parent support, accounts and schedules, orientation meetings. Built the Quadrant Display system ↓</sub> | TUMO Center for Creative Technologies | `08/2026 — now` |
| 🧑‍🏫 | **Volunteer Instructor** <br/><sub>Taught C and Linux/Bash to large groups, organized events, proctored exams</sub> | 42 Yerevan & TUMO Labs | `08/2026 — now` |
| 🌐 | **Technical Support Specialist** <br/><sub>Troubleshot routers, Wi-Fi, LAN, and basic network configs</sub> | Ucom | `06/2025 — 04/2026` |
| ⛺ | **Volunteer Mentor** <br/><sub>Supervised and mentored children of different age groups</sub> | Children's Summer Camp | `07/2024, 07/2025` |

## `$ ./featured`

### 📺 Quadrant Display Automation (TUMO)

![Google Apps Script](https://img.shields.io/badge/Google_Apps_Script-4285F4?style=flat-square&logo=google&logoColor=white)
![JavaScript](https://img.shields.io/badge/HTML_/_CSS_/_JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

Staff used to update the center's schedule screens by hand. Now the screens read live data from Google Sheets and update themselves.

```mermaid
flowchart LR
    A[📊 Google Sheets<br/>staff edit as usual] --> B[⚙️ Apps Script<br/>format-aware parser]
    B --> C[🌐 Web app<br/>+ admin panel]
    C --> D[🍓 Raspberry Pi<br/>Chromium kiosk]
    D --> E[🖥️ Screen 1 · coaches]
    D --> F[🖥️ Screen 2 · rooms]
```

- **Robust parsing.** The parser finds data blocks by cell formatting, so it doesn't break when staff move rows or delete headers.
- **Admin panel.** Auto and manual modes, manual edits, and one-time overrides that expire on their own.
- **Kiosk deployment.** A Raspberry Pi drives two monitors and opens Chromium full screen at boot.

## `$ ls ~/42`

<table>
<tr>
<td width="50%" valign="top">

### [🔀 push_swap](https://github.com/arthavagyan/Push_swap)
![](https://img.shields.io/badge/Radix_·_Chunk-30476b?style=flat-square) ![](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)

Sorts a stack of integers with two stacks and a limited set of operations, in the **minimum number of moves**. Includes a bitwise radix sort on stacks.

</td>
<td width="50%" valign="top">

### [🖨️ ft_printf](https://github.com/arthavagyan/Printf)
![](https://img.shields.io/badge/Variadic_functions-30476b?style=flat-square) ![](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)

My own `printf` built on `<stdarg.h>`. Handles flags, width, precision, and padding, with hex and pointer conversion written from scratch.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [📄 get_next_line](https://github.com/arthavagyan/get_next_line)
![](https://img.shields.io/badge/Static_variables-30476b?style=flat-square) ![](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)

Reads a file descriptor line by line with any `BUFFER_SIZE`, from 1 to 10,000,000. **Zero leaks** under Valgrind.

</td>
<td width="50%" valign="top">

### [🧱 libft](https://github.com/arthavagyan/libft)
![](https://img.shields.io/badge/Memory_management-30476b?style=flat-square) ![](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)

My own libc: `memmove`, string utilities, and a linked-list API. Every later 42 project is built on it.

</td>
</tr>
</table>

## `$ which tools`

<div align="center">

<img src="https://skillicons.dev/icons?i=c,python,bash,linux,git,raspberrypi,html,css,js&perline=9" alt="C, Python, Bash, Linux, Git, Raspberry Pi, HTML, CSS, JS" />

<br/><br/>

![Google Apps Script](https://img.shields.io/badge/Google_Apps_Script-0d1117?style=for-the-badge&logo=google&logoColor=4285F4)
![Google Workspace](https://img.shields.io/badge/Google_Workspace-0d1117?style=for-the-badge&logo=googledrive&logoColor=34A853)
![MS Office](https://img.shields.io/badge/MS_Office-0d1117?style=for-the-badge&logo=microsoftoffice&logoColor=D83B01)
![Networking](https://img.shields.io/badge/Networking-0d1117?style=for-the-badge&logo=cisco&logoColor=1BA0D7)

</div>

<table>
<tr>
<td width="50%" valign="top">

**🧠 Fundamentals**

`Algorithms & Data Structures` `Memory Management`
`Digital Logic` `Computer Architecture`
`Networking` `Linux / Unix`

</td>
<td width="50%" valign="top">

**🤝 How I work**

`Peer-to-Peer Collaboration` `Self-Learning`
`Problem Solving` `Critical Thinking` `Persistence`
`Teamwork` `Communication` `Time Management`

</td>
</tr>
</table>

## `$ locale -a`

| Language | Level | |
|:--|:-:|:--|
| 🇦🇲 Armenian | Native | `██████████` |
| 🇷🇺 Russian | C1 | `████████░░` |
| 🇬🇧 English | B2 | `███████░░░` |

## `$ git log --stat`

<div align="center">

<img src="https://github-readme-streak-stats-eight.vercel.app/?user=arthavagyan&theme=github-dark-blue&hide_border=true&border_radius=10" alt="Streak stats" width="49%" />
<img src="https://github-readme-stats.shion.dev/api/top-langs/?username=arthavagyan&theme=github_dark&hide_border=true&layout=compact&border_radius=10" alt="Top languages" width="49%" />

<br/><br/>

<img src="assets/footer.svg" width="100%" alt="while (alive) { learn(); build(); share(); }" />

</div>
