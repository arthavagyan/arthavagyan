<div align="center">

<img src="assets/header.svg" width="100%" alt="Arthur Avagyan — Software Engineering Student · C · Linux · Python" />

<br/>

<a href="mailto:arthavagy@gmail.com"><img src="assets/c-email.svg" width="420" alt="Email: arthavagy@gmail.com" /></a>
<a href="https://linkedin.com/in/arthavagyan"><img src="assets/c-linkedin.svg" width="220" alt="LinkedIn: @arthavagyan" /></a>
<br/>
<a href="https://drive.google.com/file/d/1Wg4sBJCw-wbwnl68sQes4tj4FEUyJxB6/view?usp=sharing"><img src="assets/c-cv.svg" width="220" alt="CV (PDF on Google Drive)" /></a>
<img src="assets/c-location.svg" width="420" alt="Yerevan, Armenia" />

</div>

## `$ neofetch`

<img src="assets/neofetch.svg" width="100%" alt="neofetch — Arthur Avagyan: NPUA, 42 Yerevan, TUMO; C, Python, Bash" />

I'm a final-year Applied Mathematics & Informatics student at **NPUA**, and at the same time I'm training as a software engineer at **42 Yerevan**. 42's peer-to-peer model taught me to learn on my own, read other people's code, and debug without a teacher. At **TUMO** I built an automated schedule-display system that now runs the center's information screens. I also teach C and Linux to other students, because explaining something is the best test of whether you understand it.

## `$ git log --graph`

<img src="assets/experience.svg" width="100%" alt="Experience: TUMO Information Desk Coordinator (08/2026–now); volunteer instructor at 42 Yerevan & TUMO Labs (08/2026–now); Technical Support Specialist at Ucom (06/2025–04/2026); volunteer mentor at Children's Summer Camp (07/2024, 07/2025)" />

## `$ ./featured`

### 📺 Quadrant Display Automation (TUMO)


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

<img src="assets/t-c.svg" width="200" alt="C" />
<img src="assets/t-python.svg" width="200" alt="Python" />
<img src="assets/t-bash.svg" width="200" alt="Bash" />
<img src="assets/t-linux.svg" width="200" alt="Linux" />
<br/>
<img src="assets/t-git.svg" width="200" alt="Git" />
<img src="assets/t-appsscript.svg" width="200" alt="Google Apps Script" />
<img src="assets/t-raspberrypi.svg" width="200" alt="Raspberry Pi" />
<img src="assets/t-js.svg" width="200" alt="HTML/CSS/JS" />

</div>

<table>
<tr>
<td width="50%" valign="top">

**🧠 Fundamentals**

`Algorithms & Data Structures` `Memory Management`
`Digital Logic` `Computer Architecture`
`Networking` `Linux / Unix`
`Google Workspace` `MS Office`

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

## `$ gh stats`

<div align="center">

<img src="https://github-readme-streak-stats-eight.vercel.app/?user=arthavagyan&theme=github-dark-blue&hide_border=true&border_radius=10" alt="Streak stats" width="49%" />
<img src="https://github-readme-stats.shion.dev/api/top-langs/?username=arthavagyan&theme=github_dark&hide_border=true&layout=compact&border_radius=10" alt="Top languages" width="49%" />

<br/><br/>

<img src="assets/footer.svg" width="100%" alt="while (alive) { learn(); build(); share(); }" />

</div>
