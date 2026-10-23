---
title: ''
summary: '张霖的个人学术主页：VSLAM、机器人导航、计算机视觉与无人系统研究。'
date: 2026-08-11
type: landing

sections:
  - block: resume-biography-3
    id: about
    content:
      username: me
      text: ''
      headings:
        about: 关于我
        education: 教育经历
        interests: 研究兴趣
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: lg
      avatar:
        size: large
        shape: rounded

  - block: markdown
    id: research
    content:
      title: 研究方向
      subtitle: Research Focus
      text: |-
        我关注复杂环境下的**视觉同步定位与建图（VSLAM）**，希望让无人系统获得稳定、实时且可泛化的空间感知能力。当前兴趣集中在视觉惯性融合、鲁棒状态估计、多传感器融合，以及面向机器人自主导航的工程落地。

        本科期间，我围绕 ROS 移动机器人、SLAM 建图、MoveBase 导航、视觉巡线和低延迟视频传输开展了多项实践。接下来将在北京航空航天大学无人系统研究院继续深入 VSLAM 方向研究。
    design:
      columns: '1'

  - block: collection
    id: projects
    content:
      title: 代表项目
      subtitle: Selected Projects
      text: 从感知、定位到规划与控制的完整机器人系统实践。
      filters:
        folders:
          - projects
    design:
      view: card
      columns: 3
      show_date: false
      show_read_time: false
      show_read_more: true

  - block: resume-experience
    id: experience
    content:
      title: 经历
      username: me
    design:
      date_format: '2006.01'
      is_education_first: false

  - block: resume-awards
    id: awards
    content:
      title: 竞赛与荣誉
      username: me

  - block: resume-skills
    id: skills
    content:
      title: 技术能力
      username: me
---
