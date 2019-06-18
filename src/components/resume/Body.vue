<template>
    <div>
        <div class="resume-body-sidebar">
            <div class="nav-sidebar"><a href="#basicInfo">基本信息</a></div>
            <div class="nav-sidebar"><a href="#workExperience">工作经历</a></div>
            <div class="nav-sidebar"><a href="#projectExperience">项目经验</a></div>
            <div class="nav-sidebar"><a href="#educationExperience">教育经历</a></div>
            <div class="nav-sidebar"><a href="#selfEvaluation">自我评价</a></div>
            <div class="split-line"></div>
        </div>
        <div class="resume-body-content">
            <div class="basic-info">
                <div id="basicInfo" class="info-title">基本信息</div>
                <div class="info-detail">
                   <div style="margin-left: 5vw;text-align: left;">
                        <span>姓名：李卫&nbsp;</span>
                        <span>手机号： 1234567878</span>
                   </div>
                </div>
            </div>
            <div class="work-experience">
                <div id="workExperience" class="info-title">工作经历</div>
                <div class="info-detail">
                    <el-timeline>
                        <el-timeline-item timestamp="2015/07-2017/08" placement="top">
                            <el-card>
                                <div class="job-info">
                                    <div class="company">公司：<span>东华软件股份公司</span></div>
                                    <div class="job">岗位：<span>Web前端开发</span></div>
                                </div>
                                <div class="job-detail">
                                    <span>工作描述：</span>
                                    <span>
                                            本人为长期驻点工程师，长期一个人处理项目上的问题，服务于本项目期间推动项目验收成功。
                                            所在项目是基于hibernate和Struts2框架并使用jQuery库的web应用，服务于医院医生和政府机关，主要负责工作如下：
                                            1.使用MySQL、Oracle数据库及Java语言处理后台数据问题，与医院His系统工程师沟通，并提出解决方案；
                                            2.使用Java、Js语言和JSP技术处理系统问题，根据客户所提需求，实现相应功能或对已有功能进行优化；
                                            3.处理用户使用问题，用户使用系统的电脑环境不同，且对电脑了解程度不同，对使用遇到的问题进行解答，提供技术支持。
                                    </span>
                                </div>
                            </el-card>
                        </el-timeline-item>
                        <el-timeline-item timestamp="2017/10-2019/04" placement="top">
                            <el-card>
                                <div class="job-info">
                                    <div class="company">公司：<span>中软国际有限公司</span></div>
                                    <div class="job">岗位：<span>Web前端开发</span></div>
                                </div>
                                <div class="job-detail">
                                    <span>工作描述：</span>
                                    <span>
                                            入职后至今先后参与华泰证券3个中后台管理项目和1个前台展示项目，期间负责主要的前端页面构建以及部分后端接口和数据库操作代码编写，
                                            熟悉并掌握了一个项目从开发到发布的全过程，在项目实践和不断的自学中了解了更多前沿知识和技术。
                                    </span>
                                </div>
                            </el-card>
                        </el-timeline-item>
                    </el-timeline>
                </div>
            </div>
            <div class="project-experence">
                <div id="projectExperience" class="info-title">项目经验</div>
            </div>
            <div class="education-experience">
                <div id="educationExperience" class="info-title">教育经历</div>
                <div class="info-detail">
                    <el-timeline>
                        <el-timeline-item timestamp="2008/09-2011/07" placement="top">
                            <el-card>
                                <h3>就读于泌阳县第一高级中学</h3>
                                <p>在校期间学习了数理化等知识，并对计算机有了初步兴趣。</p>
                            </el-card>
                        </el-timeline-item>
                        <el-timeline-item timestamp="2011/09-2015/07" placement="top">
                            <el-card>
                                <h3>就读于<a href="http://www.chd.edu.cn/338/list.htm">长安大学</a>信息学院软件工程专业</h3>
                                <p>在校期间学习了Ｃ＋＋、Java等编程语言，以及算法与数据结构、计算机网络、操作系统以及Linux系统等知识。</p>
                            </el-card>
                        </el-timeline-item>
                    </el-timeline>
                </div>
            </div>
            <div class="self-evaluation">
                <div id="selfEvaluation" class="info-title">自我评估</div>
                <div class="info-detail">
                    <!-- <p>
                            本人长安大学（211）本科毕业，英语能力良好，参加工作已近4年，期间学习并掌握了前端相关技术。主要掌握技能如下：
                            
                            
                            本人GitHub地址为https://github.com/codeoD，曾因工作学习需要部分翻译了spring boot的英文文档。虽然现在对开源还没有太多贡献，但本人热爱开源项目，
                            喜欢探索前沿技术，希望有朝一日在开源领域可以做出自己的成就。
                    </p> -->
                    <div class="self-summary">本人长安大学（211）本科毕业，英语能力良好，参加工作已近4年，期间学习并掌握了前端相关技术。主要掌握技能如下：</div>
                    <ul class="skill-list">
                        <li>熟练使用Java、JS编程语言</li>
                        <li>熟练使用Ajax、DOM操作技术</li>
                        <li>熟练使用Vue及相关技术（vue-router等）</li>
                        <li>熟练使用echarts，对d3有过了解</li>
                        <li>熟练使用jest单元测试框架</li>
                        <li>熟悉webpack、standardjs、axios、scss</li>
                        <li>熟悉typescript</li>
                        <li>熟悉graphql</li>
                        <li>熟悉spring boot、mybatis</li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</template>
<style lang="scss">
.resume-body-sidebar {
    position: relative;
    display: inline-block;
    width: 20%;
    height: 100%;
    .nav-sidebar {
        margin-top: 4vh;
        &:first-child {
            margin-top: 12vh;
        }
    }
    .split-line {
        position: absolute;
        width: 1px;
        height: 75%;
        top: 5%;
        right: 0;
        content: '';
        background-color: #c4bef5;
    }
}
.resume-body-content {
    display: inline-block;
    width: 80%;
    height: 100%;
    vertical-align: top;
    & > div {
        margin-top: 2vh;
        margin-bottom: 1vh;
        .info-title {
            margin: 2vh 4vw;
            text-align: left;
            font-weight: 700;
        }
        .info-detail {
            .el-timeline {
                width: 80%;
                margin-left: 5vw;
                text-align: left;
            }
            .job-info {
                text-align: left;
                .company {
                    margin: 1vh 0;
                    font-weight: 700;
                }
                .job {
                    margin: 1vh 0;
                    font-weight: 700;
                }
            }
            .job-detail > span:first-child {
                font-weight: 700;
            }
            .self-summary {
                width: 80%;
            }
            .skill-list {
                width: 80%;
                margin-left: 8vw;
                text-align: left;
                li {
                    margin: 0.5vh 0;
                }
            }
        }
    }
}
</style>