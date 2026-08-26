---
theme: seriph
title: From Coding to Software Engineering
info: |
  ## Coding to Software Engineering
  从写代码到做软件 · 小猴偷米 Herald Studio
author: 小猴偷米 Herald Studio
class: text-left
colorSchema: light
themeConfig:
  primary: "#13acd9"
transition: slide-left
mdc: true
drawings:
  persist: false
fonts:
  provider: none
  sans: "PingFang SC, Microsoft YaHei, Noto Sans SC, ui-sans-serif, system-ui"
  serif: "Songti SC, Noto Serif SC, ui-serif, serif"
  mono: "JetBrains Mono, Menlo, Consolas, monospace"
layout: default
duration: 25min
---

<div class="h-full flex flex-col justify-center">

<h1 class="deck-title color-[var(--slidev-theme-primary)]! text-5xl! leading-tight! mb-2">From <span class="relative inline-block font-extrabold">Coding<svg class="absolute left-0 w-full h-[0.13em] pointer-events-none" style="bottom: -0.04em" viewBox="0 0 100 8" preserveAspectRatio="none" aria-hidden="true"><path d="M1 4.7 C20 3.5, 39 5.7, 59 4.4 S83 3.7, 99 4.6" fill="none" stroke="#13acd9" stroke-width="1.8" stroke-linecap="round"/><path d="M2 6 C24 4.9, 46 6.2, 68 5.3 S88 5, 98 5.5" fill="none" stroke="#13acd9" stroke-width="0.9" stroke-linecap="round" opacity="0.55"/></svg></span><br/>to <span class="relative inline-block font-extrabold">Software Engineering<svg class="absolute left-0 w-full h-[0.13em] pointer-events-none" style="bottom: -0.04em" viewBox="0 0 100 8" preserveAspectRatio="none" aria-hidden="true"><path d="M1 4.7 C20 3.5, 39 5.7, 59 4.4 S83 3.7, 99 4.6" fill="none" stroke="#13acd9" stroke-width="1.8" stroke-linecap="round"/><path d="M2 6 C24 4.9, 46 6.2, 68 5.3 S88 5, 98 5.5" fill="none" stroke="#13acd9" stroke-width="0.9" stroke-linecap="round" opacity="0.55"/></svg></span></h1>

<div class="w-16 h-1 bg-[var(--slidev-theme-primary)] rounded-full opacity-60 mb-3"></div>

<div class="mb-8 font-sans text-[13px] font-bold tracking-[0.12em] leading-none color-[var(--slidev-theme-primary)]!">{{ new Date().getFullYear() }}年{{ new Date().getMonth() + 1 }}月{{ new Date().getDate() }}日</div>

<div class="flex items-start gap-4 text-[11px] leading-none opacity-80">

<div class="flex flex-col gap-1.5">
<span class="text-[9px] tracking-[0.16em] opacity-70 font-semibold">PRESENTER</span>
<div class="flex items-center gap-1.5 pr-3 rounded-full bg-white/50 ring-1 ring-gray-300/40">
<img src="/avatar/yuanzihan.jpg" class="w-5 h-5 rounded-full object-cover block" />
<span>袁梓涵</span>
<span class="opacity-40">yuanzihan</span>
</div>
</div>

<div class="flex flex-col gap-1.5">
<span class="text-[9px] tracking-[0.16em] opacity-0">PRESENTER</span>
<div class="flex items-center gap-1.5 pr-3 rounded-full bg-white/50 ring-1 ring-gray-300/40">
<img src="/avatar/isy.jpg" class="w-5 h-5 rounded-full object-cover block" />
<span>李承恩</span>
<span class="opacity-40">Isy</span>
</div>
</div>

<div class="flex flex-col gap-1.5">
<span class="text-[9px] tracking-[0.16em] opacity-0">PRESENTER</span>
<div class="flex items-center gap-1.5 pr-3 rounded-full bg-white/50 ring-1 ring-gray-300/40">
<img src="/avatar/shiyudesu.jpg" class="w-5 h-5 rounded-full object-cover block" />
<span>张宸铭</span>
<span class="opacity-40">shiyudesu</span>
</div>
</div>

<div class="flex flex-col gap-1.5">
<span class="text-[9px] tracking-[0.16em] opacity-70 font-semibold">SLIDES</span>
<div class="flex items-center gap-1.5 pr-3 rounded-full bg-white/50 ring-1 ring-gray-300/40">
<img src="/avatar/elecmonkey.jpg" class="w-5 h-5 rounded-full object-cover block" />
<span>李厚之</span>
<span class="opacity-40">Elecmonkey</span>
</div>
</div>

</div>

<div class="mt-10 text-sm leading-none">
<div class="flex items-center gap-2 color-[var(--slidev-theme-primary)]!">
<img src="/tommy.png" class="w-5 h-5 object-contain" />
<div class="flex items-baseline gap-2.5">
<span class="font-sans font-bold">信使计划工作室</span><span>Herald Studio</span>
</div>
</div>
</div>

</div>

---
layout: two-cols-header
---

# 课堂中的代码

::left::

<div class="text-xs opacity-50 mb-2">课程里的一个常见例子</div>

```cpp
void bubbleSort(vector<int>& nums) {
    int n = nums.size();
    for (int i = 0; i < n - 1; ++i) {
        bool swapped = false;
        for (int j = 0; j < n - i - 1; ++j) {
            if (nums[j] > nums[j + 1]) {
                swap(nums[j], nums[j + 1]);
                swapped = true;
            }
        }
        if (!swapped) break;
    }
}
```

::right::

<div class="pl-4">
<v-clicks>

<div class="flex items-center gap-2 mb-3">
<div class="w-1.5 h-1.5 rounded-full bg-gray-400"></div>
<span class="text-sm">算法题、课程实验、小组项目，形式都很常见</span>
</div>

<div class="flex items-center gap-2 mb-3">
<div class="w-1.5 h-1.5 rounded-full bg-gray-400"></div>
<span class="text-sm">老师给出验收标准和截止日期</span>
</div>

<div class="flex items-center gap-2 mb-3">
<div class="w-1.5 h-1.5 rounded-full bg-gray-400"></div>
<span class="text-sm">交付通常是代码、报告或一次课堂演示</span>
</div>

<div class="flex items-center gap-2 mb-3">
<div class="w-1.5 h-1.5 rounded-full bg-gray-400"></div>
<span class="text-sm">很少部署给真实用户持续使用</span>
</div>

<div class="flex items-center gap-2">
<div class="w-1.5 h-1.5 rounded-full bg-gray-400"></div>
<span class="text-sm">课程结束后，代码通常也停在那一版</span>
</div>

</v-clicks>
</div>

---
layout: default
---

# 可是，真实的软件工程流程是……

<div class="grid grid-cols-[1.15fr_0.85fr] gap-6 mt-6">

<div class="grid grid-cols-2 gap-3">

<div v-click class="p-3 rounded-lg border border-gray-200 bg-white/65">
<div class="text-xs font-bold color-[var(--slidev-theme-primary)]! mb-1">01 · 技术选型</div>
<div class="text-xs opacity-75">语言、框架、数据库和部署方式怎么选。</div>
</div>

<div v-click class="p-3 rounded-lg border border-gray-200 bg-white/65">
<div class="text-xs font-bold color-[var(--slidev-theme-primary)]! mb-1">02 · 系统设计</div>
<div class="text-xs opacity-75">模块怎么拆，接口、数据和权限怎么组织。</div>
</div>

<div v-click class="p-3 rounded-lg border border-gray-200 bg-white/65">
<div class="text-xs font-bold color-[var(--slidev-theme-primary)]! mb-1">03 · 编码与协作</div>
<div class="text-xs opacity-75">Git、代码规范、评审，以及前后端联调。</div>
</div>

<div v-click class="p-3 rounded-lg border border-gray-200 bg-white/65">
<div class="text-xs font-bold color-[var(--slidev-theme-primary)]! mb-1">04 · 测试与排障</div>
<div class="text-xs opacity-75">测试、日志、性能，以及异常和边界情况。</div>
</div>

<div v-click class="p-3 rounded-lg border border-gray-200 bg-white/65">
<div class="text-xs font-bold color-[var(--slidev-theme-primary)]! mb-1">05 · 部署与运行</div>
<div class="text-xs opacity-75">构建、环境配置、容器、监控和备份。</div>
</div>

<div v-click class="p-3 rounded-lg border border-gray-200 bg-white/65">
<div class="text-xs font-bold color-[var(--slidev-theme-primary)]! mb-1">06 · 迭代与维护</div>
<div class="text-xs opacity-75">修 Bug、升级依赖、重构和兼容历史数据。</div>
</div>

</div>

<div v-click class="flex flex-col justify-center">
<img src="/screenshot/counseling-center.png" class="w-full h-56 object-cover object-top rounded-lg border border-gray-200 shadow-sm" />
<div class="mt-2 text-center text-xs opacity-55">心理中心咨询系统</div>
</div>

</div>

<div v-click class="mt-6 p-3 rounded-lg bg-[#13acd9]/8 border border-[#13acd9]/25 text-center text-sm font-medium">
到了真实项目里，我们大部分时间在处理这些问题，几乎不会手写冒泡排序。
</div>

---

# 项目是一版一版改出来的

<div class="mt-5 text-sm opacity-65">
技术方案、代码和上线后的运行情况，都要根据真实使用继续调整。
</div>

<div class="mt-6">

```mermaid {scale: 0.62}
graph LR
  V0["最初版本<br/>只有一个核心功能<br/>界面很糙"] --> V1["能用起来<br/>补齐主流程<br/>修一堆 Bug"]
  V1 --> V2["有人真的在用<br/>性能 · 稳定性<br/>开始被追着提需求"]
  V2 --> V3["重构 / 换方案<br/>补文档和测试<br/>交接给下一届"]
```

</div>

<div class="grid grid-cols-2 gap-6 mt-8">

<div v-click class="p-4 rounded-lg bg-gray-50">

**第一版只做了最核心的功能**

很多细节还没处理，
先拿来测试，再根据问题继续改。

</div>

<div v-click class="p-4 rounded-lg bg-gray-50">

**后面的版本逐步补齐**

功能、性能、文档和交接，
都是在使用过程中加进去的。

</div>

</div>

---
layout: two-cols-header
---

# 印象最深的几个坑

::left::

<v-clicks>

<div class="p-3 rounded bg-red-50 border border-red-100 mb-3">
<div class="font-bold text-sm">🐛 那个 Bug</div>
<div class="text-sm opacity-75">本地一直复现不了，线上却持续报错，只能对着日志和运行环境逐项排查。</div>
</div>

<div class="p-3 rounded bg-orange-50 border border-orange-100 mb-3">
<div class="font-bold text-sm">🔁 那个重做的功能</div>
<div class="text-sm opacity-75">第一版设计没考虑到某种情况，加需求时越改越乱，最后推倒重来。</div>
</div>

<div class="p-3 rounded bg-blue-50 border border-blue-100">
<div class="font-bold text-sm">🚀 第一次部署 / 联调</div>
<div class="text-sm opacity-75">本地跑得好好的，一上服务器全是问题；前后端字段对不上，互相都以为是对方的锅。</div>
</div>

</v-clicks>

::right::

<div class="pl-6 pt-4">

<div v-click class="p-5 rounded-lg border-2 border-teal-500 bg-teal-50/40">

### 这些经历教会我的

<div class="mt-3 space-y-2 text-sm">

- 出问题先**看日志、看报错**，不要凭感觉猜

- 能**稳定复现**，Bug 就解决一半了

- **一次只改一个地方**，不然不知道是哪一下修好的

- 项目的生命周期**比人长**——文档写细一点，两年后接手的学弟学妹会感谢你

</div>

</div>

</div>

---

# 课堂代码和真实开发，差在哪？

<div class="grid grid-cols-2 gap-6 mt-6">

<div v-click class="p-5 rounded-lg border border-gray-200">

### 课程作业

- 按要求完成并提交
- 验收方式是测试、报告或演示
- 大多只在本地运行
- 使用者是自己、同学和老师
- 周期通常只有几周

</div>

<div v-click class="p-5 rounded-lg border-2 border-[#13acd9] bg-[#13acd9]/5">

### 长期运行的软件

- 技术方案需要自己选择和调整
- 部署到服务器和真实环境
- 用户、数据和异常情况持续出现
- 通过日志定位并解决线上问题
- 几个月甚至几年持续更新

</div>

</div>

<div v-click class="mt-8 text-center text-lg">
作业通常交完就结束；上线后的软件还要<span v-mark.underline.orange>继续处理问题和更新</span>
</div>

---
layout: default
---

# 我们的专业课

<div class="relative h-[360px] mt-10">

<div v-click class="absolute left-[1%] top-7 w-[30%] min-h-[235px] p-5 rounded-xl border border-t-4 shadow-md" style="transform: rotate(-4deg); background: color-mix(in srgb, var(--slidev-theme-primary) 5%, white); border-color: color-mix(in srgb, var(--slidev-theme-primary) 24%, white); border-top-color: color-mix(in srgb, var(--slidev-theme-primary) 65%, white)">
<div class="text-xs font-bold mb-3 color-[var(--slidev-theme-primary)]! opacity-65">01</div>
<div class="text-xl font-bold mb-4">数据结构与算法</div>
<div class="text-sm leading-relaxed opacity-75">数据结构决定数据怎样组织和访问。算法训练让你能判断时间和空间开销，遇到性能问题时知道从哪里查。</div>
</div>

<div v-click class="absolute left-[34.5%] top-0 w-[31%] min-h-[245px] p-5 rounded-xl border border-t-4 shadow-md" style="transform: rotate(2.5deg); background: color-mix(in srgb, var(--slidev-theme-primary) 8%, white); border-color: color-mix(in srgb, var(--slidev-theme-primary) 30%, white); border-top-color: color-mix(in srgb, var(--slidev-theme-primary) 75%, white)">
<div class="text-xs font-bold mb-3 color-[var(--slidev-theme-primary)]! opacity-75">02</div>
<div class="text-xl font-bold mb-4">软件工程导论</div>
<div class="text-sm leading-relaxed opacity-75">课程会讲需求、设计、测试、版本管理和协作流程。团队项目做久了，就会知道这些步骤分别在解决什么问题。</div>
</div>

<div v-click class="absolute right-[1%] top-9 w-[30%] min-h-[235px] p-5 rounded-xl border border-t-4 shadow-md" style="transform: rotate(-3deg); background: color-mix(in srgb, var(--slidev-theme-primary) 11%, white); border-color: color-mix(in srgb, var(--slidev-theme-primary) 36%, white); border-top-color: color-mix(in srgb, var(--slidev-theme-primary) 85%, white)">
<div class="text-xs font-bold mb-3 color-[var(--slidev-theme-primary)]! opacity-85">03</div>
<div class="text-xl font-bold mb-4">操作系统</div>
<div class="text-sm leading-relaxed opacity-75">程序最后都要交给操作系统运行。进程、线程、内存和 I/O，是排查并发、资源占用和性能问题的基础。</div>
</div>

</div>

---
layout: default
---

# 我们的专业课

<div class="relative h-[360px] mt-10">

<div v-click class="absolute left-[1%] top-0 w-[30%] min-h-[235px] p-5 rounded-xl border border-t-4 shadow-md" style="transform: rotate(3deg); background: color-mix(in srgb, var(--slidev-theme-primary) 6%, white); border-color: color-mix(in srgb, var(--slidev-theme-primary) 26%, white); border-top-color: color-mix(in srgb, var(--slidev-theme-primary) 68%, white)">
<div class="text-xs font-bold mb-3 color-[var(--slidev-theme-primary)]! opacity-68">04</div>
<div class="text-xl font-bold mb-4">计算机网络</div>
<div class="text-sm leading-relaxed opacity-75">请求怎样从浏览器到服务器，连接为什么超时，代理和 HTTPS 在做什么。前后端联调、部署和线上排查都会用到。</div>
</div>

<div v-click class="absolute left-[34.5%] top-9 w-[31%] min-h-[235px] p-5 rounded-xl border border-t-4 shadow-md" style="transform: rotate(-3.5deg); background: color-mix(in srgb, var(--slidev-theme-primary) 9%, white); border-color: color-mix(in srgb, var(--slidev-theme-primary) 32%, white); border-top-color: color-mix(in srgb, var(--slidev-theme-primary) 78%, white)">
<div class="text-xs font-bold mb-3 color-[var(--slidev-theme-primary)]! opacity-78">05</div>
<div class="text-xl font-bold mb-4">数据库</div>
<div class="text-sm leading-relaxed opacity-75">表结构、索引和事务决定数据能否存对、查快。数据量和并发上来后，早期设计的问题会很快暴露。</div>
</div>

<div v-click class="absolute right-[1%] top-2 w-[31%] min-h-[255px] p-5 rounded-xl border border-t-4 shadow-md" style="transform: rotate(4deg); background: color-mix(in srgb, var(--slidev-theme-primary) 12%, white); border-color: color-mix(in srgb, var(--slidev-theme-primary) 38%, white); border-top-color: color-mix(in srgb, var(--slidev-theme-primary) 88%, white)">
<div class="text-xs font-bold mb-3 color-[var(--slidev-theme-primary)]! opacity-88">06</div>
<div class="text-xl font-bold mb-4">编译原理</div>
<div class="text-sm leading-relaxed opacity-75">普通业务开发很少直接用到，准备一直写常规业务代码，60 分及格就够。想做语言、工具链或编辑器，它是很重要的基础，这些方向也更难被 AI 替代。</div>
</div>

</div>

---
layout: two-cols-header
---

# AI 确实很好用

---
layout: default
---

# AI 写完代码以后

---

# 在 AI Agent 帮助下提升

---
layout: two-cols-header
---

# 如何用好 AI 工具

---

# 给同学们的几个建议

<div class="grid grid-cols-1 gap-3 mt-6">

<div v-click class="flex items-center gap-4 p-3 rounded-lg bg-gray-50">
<div class="text-teal-600 font-bold text-xl w-8">01</div>
<div>
<span class="font-bold">尽早完整地做一次软件开发</span>
<span class="opacity-70 text-sm"> —— 从需求到上线走通一遍，哪怕项目很小</span>
</div>
</div>

<div v-click class="flex items-center gap-4 p-3 rounded-lg bg-gray-50">
<div class="text-teal-600 font-bold text-xl w-8">02</div>
<div>
<span class="font-bold">多动手、多 Debug，不要只看教程</span>
<span class="opacity-70 text-sm"> —— 看完教程后，自己从头做一遍</span>
</div>
</div>

<div v-click class="flex items-center gap-4 p-3 rounded-lg bg-gray-50">
<div class="text-teal-600 font-bold text-xl w-8">03</div>
<div>
<span class="font-bold">学会 Git、查官方文档、自己定位问题</span>
<span class="opacity-70 text-sm"> —— 团队开发每天都会用到</span>
</div>
</div>

<div v-click class="flex items-center gap-4 p-3 rounded-lg bg-gray-50">
<div class="text-teal-600 font-bold text-xl w-8">04</div>
<div>
<span class="font-bold">有机会就多参加项目、比赛和团队开发</span>
<span class="opacity-70 text-sm"> —— 接触不同分工，也看看别人怎么写代码</span>
</div>
</div>

<div v-click class="flex items-center gap-4 p-3 rounded-lg bg-teal-50 border border-teal-200">
<div class="text-teal-600 font-bold text-xl w-8">05</div>
<div>
<span class="font-bold">攒下几个自己参与、能讲清楚的项目</span>
<span class="opacity-70 text-sm"> —— 找实习时，简历和面试都有具体内容可讲</span>
</div>
</div>

<div v-click class="flex items-center gap-4 p-3 rounded-lg bg-gray-50/50">
<div class="text-teal-600 font-bold text-xl w-8 opacity-50 line-through">06</div>
<div class="font-bold opacity-50 line-through">加入我们</div>
</div>

</div>

---
layout: default
---

# 我们在做这些

<div class="grid grid-cols-3 gap-3 mt-6">

<div v-click class="rounded-lg border border-gray-200 overflow-hidden">
<img src="/screenshot/counseling-center.png" class="h-28 w-full object-cover object-top" />
<div class="p-3">
<div class="font-bold text-sm">心理中心咨询系统</div>
<div class="flex items-center gap-2 mt-2 opacity-80"><ReactIcon /><ViteIcon /><JavaIcon /><KotlinIcon /><SpringIcon /><MysqlIcon /></div>
</div>
</div>

<div v-click class="rounded-lg border border-gray-200 overflow-hidden">
<img src="/screenshot/student-affairs-mini-program.png" class="h-28 w-full object-cover object-top" />
<div class="p-3">
<div class="font-bold text-sm">学工部小程序</div>
<div class="flex items-center gap-2 mt-2 opacity-80"><VueIcon /><ViteIcon /><GoIcon /><NodeIcon /><OracleIcon /></div>
</div>
</div>

<div v-click class="rounded-lg border border-gray-200 overflow-hidden">
<img src="/screenshot/mentor-lounge.png" class="h-28 w-full object-cover object-top" />
<div class="p-3">
<div class="font-bold text-sm">信息学院导师会客厅</div>
<div class="flex items-center gap-2 mt-2 opacity-80"><VueIcon /><RsbuildIcon /><JavaIcon /><SpringIcon /><MysqlIcon /></div>
</div>
</div>

<div v-click class="rounded-lg border border-gray-200 overflow-hidden">
<img src="/screenshot/student-affairs-english-website.png" class="h-28 w-full object-cover object-top" />
<div class="p-3">
<div class="font-bold text-sm">学生处英文官网</div>
<div class="flex items-center gap-2 mt-2 opacity-80"><AstroIcon /><TailwindIcon /></div>
</div>
</div>

<div v-click class="rounded-lg border border-gray-200 overflow-hidden">
<div class="h-28 w-full overflow-hidden bg-gray-50">
<img src="/screenshot/party-history-knowledge-contest.png" class="h-full w-auto max-w-none" />
</div>
<div class="p-3">
<div class="font-bold text-sm">党史国情知识竞赛</div>
<div class="flex items-center gap-2 mt-2 opacity-80"><VueIcon /><ViteIcon /><GoIcon /><MysqlIcon /></div>
</div>
</div>

<div v-click class="rounded-lg border-2 border-[#13acd9] bg-[#13acd9]/5 flex items-center justify-center p-4 text-center">
<div class="font-bold text-lg tracking-widest text-[#13acd9]">AND MORE…</div>
</div>

</div>

---
layout: default
---

# 你将接触到

<div class="grid grid-cols-6 gap-x-4 gap-y-5 mt-5">

<div v-click class="col-span-2">
<img src="/directions/ai-agent.png" class="w-full h-[112px] object-cover object-top shadow-md border-b-3 border-[var(--slidev-theme-primary)]" />
<div class="mt-2 text-[15px] font-bold color-[var(--slidev-theme-primary)]!">AI Agent 开发</div>
</div>

<div v-click class="col-span-2">
<img src="/directions/enterprise-backend.png" class="w-full h-[112px] object-cover object-top shadow-md border-b-3 border-[var(--slidev-theme-primary)] opacity-95" />
<div class="mt-2 text-[15px] font-bold color-[var(--slidev-theme-primary)]!">企业级后端应用构建</div>
</div>

<div v-click class="col-span-2">
<img src="/directions/frontend-engineering.png" class="w-full h-[112px] object-cover object-top shadow-md border-b-3 border-[var(--slidev-theme-primary)] opacity-90" />
<div class="mt-2 text-[15px] font-bold color-[var(--slidev-theme-primary)]!">前沿前端工程</div>
</div>

<div v-click class="col-span-3">
<img src="/directions/database-design.jpeg" class="w-full h-[112px] object-cover object-center shadow-md border-b-3 border-[var(--slidev-theme-primary)] opacity-85" />
<div class="mt-2 text-[15px] font-bold color-[var(--slidev-theme-primary)]!">高性能数据库设计</div>
</div>

<div v-click class="col-span-3">
<div class="grid gap-2" style="grid-template-columns: 1.35fr 1fr; height: 112px">
<img src="/directions/cicd-devops.png" class="block w-full object-cover object-left shadow-md border-b-3 border-[var(--slidev-theme-primary)]" style="height: 112px" />
<img src="/directions/linux-ssh.png" class="block w-full object-cover object-center shadow-md border-b-3 border-[var(--slidev-theme-primary)] opacity-90" style="height: 112px" />
</div>
<div class="mt-3 text-[15px] leading-none font-bold color-[var(--slidev-theme-primary)]!">Linux 与 DevOps</div>
</div>

</div>

<div v-click class="mt-3 text-right text-xl font-extrabold tracking-[0.18em] color-[var(--slidev-theme-primary)]! opacity-75">AND MORE…</div>

---
layout: default
---

# 你还能得到……

<div class="relative h-[370px] mt-2">

<div class="absolute right-2 top-1 text-xs tracking-widest opacity-40">技术 · 项目 · 实习 · 工作</div>

<svg class="absolute inset-0 w-full h-full pointer-events-none" viewBox="0 0 900 370" aria-hidden="true">
  <path d="M430 175 C505 120, 535 225, 610 180" fill="none" stroke="var(--slidev-theme-primary)" stroke-width="2" stroke-dasharray="7 9" opacity="0.32" />
  <circle cx="444" cy="166" r="5" fill="var(--slidev-theme-primary)" opacity="0.32" />
  <circle cx="596" cy="188" r="5" fill="var(--slidev-theme-primary)" opacity="0.32" />
</svg>

<div v-click class="absolute left-2 top-4 w-[51%]" style="transform: rotate(-2deg)">
<img src="/screenshot/tech-salon.png" class="w-full border-[6px] border-white shadow-xl" />
<div class="mt-3 ml-2">
<div class="text-2xl font-bold">技术沙龙</div>
<div class="w-16 h-1 bg-[var(--slidev-theme-primary)] opacity-55 mt-2 mb-3" style="transform: rotate(-2deg)"></div>
<div class="text-sm leading-relaxed opacity-65">在讨论与分享中最快的进步。</div>
</div>
</div>

<div v-click class="absolute right-1 top-20 w-[40%]" style="transform: rotate(2deg)">
<div class="text-3xl color-[var(--slidev-theme-primary)]! mb-2">✦</div>
<div class="text-2xl font-bold">最优秀的朋友</div>
<div class="w-16 h-1 bg-[var(--slidev-theme-primary)] opacity-55 mt-2 mb-3" style="transform: rotate(-2deg)"></div>
<div class="text-sm leading-relaxed opacity-65">
一起做项目、参加分享，平时也会交换想法、互相帮忙。
</div>
</div>

<div class="absolute right-10 bottom-2 w-3 h-3 rounded-full bg-amber-300 opacity-70"></div>
<div class="absolute right-20 bottom-8 w-2 h-2 rounded-full bg-teal-400 opacity-60"></div>

</div>

---
layout: default
---

<div class="grid grid-cols-2 h-full items-center gap-16">

<div class="text-center">
<h1 class="closing-title color-[var(--slidev-theme-primary)]! text-6xl!">Thanks</h1>

<div class="mt-8">
<div class="text-sm opacity-50 mb-3">访问招新官网</div>
<a href="https://myseu.cn" target="_blank" class="text-2xl font-semibold color-[var(--slidev-theme-primary)]!">myseu.cn</a>
</div>

<div class="mt-5">
<div class="text-xs opacity-50 mb-2">本 PPT 地址</div>
<a href="https://tommy-se.edev.uno" target="_blank" class="text-lg font-semibold color-[var(--slidev-theme-primary)]!">tommy-se.edev.uno</a>
</div>

<div class="mt-4">
<div class="text-xs opacity-50 mb-2">PPT 源码见</div>
<a href="https://github.com/elecmonkey/slidev-tommy-se" target="_blank" class="text-lg font-semibold color-[var(--slidev-theme-primary)]!">github.com/elecmonkey/slidev-tommy-se</a>
</div>
</div>

<div class="text-center">
<img src="/qq-group.jpg" class="w-56 mx-auto rounded-lg border border-gray-200" />
<div class="mt-3 text-sm opacity-70">扫码加入招新 QQ 群</div>
</div>

</div>
