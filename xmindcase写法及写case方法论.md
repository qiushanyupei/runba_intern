<img width="1615" height="626" alt="image" src="https://github.com/user-attachments/assets/236bccc2-f6bf-429b-a294-6a161817fbf0" />
测试主题->分平台（APP端，PC端）->具体细分测试模块->分到最细就是测试case（格式：tc-功能测试：）->下面需要细分pc(Previous condition)前置条件和tx(test execute)测试步骤->tx后面要吊预期结果<br>
按照字典定义测功能（尽量考虑边界情况、如空值）<br>
测入口在对应逻辑下的功能<br>
测刷新后的效果<br>
多端数据同步<br>
测UI是否完全一致<br>
如果是表单中有选项关联，选了某个选项才会出现后续输入框<br>
用例要尽可能详细，傻瓜式的，明确每一个步骤,每个字段的取值都要给出<br>
如果有用例可以覆盖其他情况，就删减其他用例<br>
如果是多条用例，就算是连在一起的行为也要分开，保持足够可读性<br>
可读性很重要，如果case特别冗长，多半要切分成不同case<br>
