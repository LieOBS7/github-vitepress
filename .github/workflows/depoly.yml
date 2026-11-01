import { defineConfig } from 'vitepress'

export default defineConfig({
  lang: 'zh-CN',
  title: '神人忧天の文档',
  description: '用 Markdown 写，推一次 main 就上线',
  base: '/github-vitepress/',

  themeConfig: {
    // 顶部导航
    nav: [
      { text: '首页', link: '/' },
      { text: '开始', link: '/start' }
      { text: '关于', link: '/about' }
    ],

    // 侧边栏（没有就先留空，不报错）
    sidebar: {
      '/': [
        { text: '开始', link: '/start' },
        { text: '关于', link: '/about' }
      ]
    },

    // 右上角搜索框（本地全文搜索，零配置就能用）
    search: {
      provider: 'local'
    },

    // 每页底部“在 GitHub 上编辑此页”
    editLink: {
      pattern: 'https://github.com/LieOBS7/github-vitepress/edit/main/docs/:path',
      text: '在 GitHub 上编辑此页'
    },

    // 右上角 GitHub 图标
    socialLinks: [
      { icon: 'github', link: 'https://github.com/LieOBS7/github-vitepress' },
      { icon: 'bilibili', link: 'https://space.bilibili.com/3546744979720373' }
    ],

    footer: {
      message: '基于 MIT 协议发布',
      copyright: 'Copyright © 2026-present 神人忧天'
    }
  }
})
