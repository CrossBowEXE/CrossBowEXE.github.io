欢迎来到CrossBow_EXE的百宝箱！

# 工具箱（用Ctrl+F快捷键搜索工具！）

@CrossBow_EXE 精心整理的工具箱，是![](https://badges.toozhao.com/badges/01HBSRPDV0DNZ4XN14B7YWE06C/blue.svg)谷民共同的 选择！

## 常用

[不会百度么？](https://lab.magiconch.com/buhuibaidu.me/)

[自创数据生成器](https://www.luogu.com.cn/paste/m4tlkazp)

[chatGPT](https://c.aalib.net/tool/chatgpt/)

[洛谷搜索](https://www.oiso.cf/)

[OI Wiki](https://oi-wiki.org/)

[压行](https://mivik.gitee.io/compress)

[洛谷帮助中心](https://help.luogu.com.cn/)

[油猴下载](https://chrome.zzzmh.cn/info/dhdgffkkebhmkfjojejmpbldmpobfkfo) | [exlg](https://exlg.oss-cn-shanghai.aliyuncs.com/latest/dist/extend-luogu.min.user.js) | [OIso](https://www.luogu.com.cn/paste/8uh7o9c6)|[OIso++](https://oiso.luogu.link/index.min.user.js)

[删犇器](https://www.luogu.com.cn/blog/392304/bens-deleter)

[图片网址生成器](https://postimages.org/)

[mc自定义成就](http://mc.whitegem.net/#)

[c++模板总结](https://www.luogu.com.cn/blog/lijunxi2009/mu-ban-zong-jie)

[油猴官网](https://www.tampermonkey.net/scripts.php)

[参观人数统计](https://badges.toozhao.com/)

[函数生成器](https://www.desmos.com/calculator?lang=zh-CN)

## 数学公式类

[$\LaTeX$](https://www.luogu.com.cn/blog/IowaBattleship/latex-gong-shi-tai-quan) | [在线 $\LaTeX$ 编辑器](https://www.codecogs.com/latex/eqneditor.php?lang=zh-cn)

[oeis](https://oeis.org)

[图论编辑器](https://riverhamster.gitee.io/app/graph_editor/)

[因式分解器](https://zh.numberempire.com/factoringcalculator.php) | [分解质因数器](https://zh.numberempire.com/numberfactorizer.php) | [解方程器](https://zh.numberempire.com/equationsolver.php) | [判断质数器](https://zh.numberempire.com/primenumbers.php) | [表达式化简器](https://zh.numberempire.com/simplifyexpression.php) | [函数编辑器](https://zh.numberempire.com/graphingcalculator.php)

[时间复杂度表](https://www.luogu.com.cn/paste/cbsfe3r9)

## 教程类

[CF快速入门](https://www.luogu.com.cn/blog/ezoixx130/codeforces-advanced-tutorial)

[SPOJ注册教程](https://www.luogu.com.cn/paste/jq3nlpwu)

[UVA食用指南](https://www.luogu.com.cn/blog/supervise/eat-uva-better)

[csp初赛复习](https://www.luogu.com.cn/blog/334586/csp-pre-knowledge)

[图片OI大纲](https://i.loli.net/2018/10/22/5bcd9299869eb.png)

[最大因数个数表](https://cdn.luogu.com.cn/upload/image_hosting/d874tlcc.png)

## 刷题网站类

[洛谷](https://www.luogu.com.cn/)

[gdfzoj](http://www.gdfzoj.com:23380)

[Codeforces](https://codeforces.com/)

[ATCoder](https://atcoder.jp/)

[SPOJ](https://www.spoj.com/)

[UVA](https://onlinejudge.org/)

[vjudge](https://vjudge.net/)

## 娱乐类

[cxk](https://alpha1022.img.ihcr.top/cxk.jpg)

[神帖](/discuss/61884) | [神帖集合](https://www.luogu.com.cn/blog/FCBM71/luo-gu-shen-tie-ji-ge-chi-xu-geng-xin-post)

[恶臭数字论证器](https://lab.magiconch.com/homo)

[颜色表](https://www.luogu.com.cn/paste/taq30802)

[圆形图片](https://www.koalastothemax.com/)

[首字母查找](https://lab.magiconch.com/nbnhhsh/)

[base64](https://base64.us/)

[萌娘百科](https://zh.moegirl.org.cn/Mainpage)

[百度翻译](https://fanyi.baidu.com/)

[词汇量测试](https://preply.com/en/learn/english/test-your-vocab)

[钢琴模拟器](https://www.xiwnn.com/piano/)

[洛谷词典](https://www.luogu.com.cn/blog/FCBM71/luogu-dictionary)

[梗大全](https://www.luogu.com.cn/paste/yl506941)

[藏头诗生成器](https://cts.chazhi.net/)

主页代码查看：（控制台代码）

```
console.log(_feInstance.currentData.user.introduction)
```

代码风格转换：（by @KobeBeanBryantCox，有改动）

```cpp
#include<bits/stdc++.h>
#include<windows.h>
using namespace std;
string s,ans="",d="{}()\'\";><=+-*/&|!^,",x[]={"return","int","long","char","bool","string","unsigned","signed","struct","auto","inline","const","float","double","register","using","namespace"};
int cnt=0;
void Copy(string TempBin)
{
	HGLOBAL hMemBin=NULL;
	PCHAR LockBin=NULL;
	OpenClipboard(NULL);
	EmptyClipboard();
	hMemBin=GlobalAlloc(GMEM_MOVEABLE,TempBin.size()+1);
	LockBin=(PCHAR)GlobalLock(hMemBin);
	RtlMoveMemory(LockBin,TempBin.c_str(),TempBin.size()+1);
	GlobalUnlock(hMemBin);
	LockBin=NULL;
	SetClipboardData(CF_TEXT,hMemBin);
	CloseClipboard();
}
bool incs(string s,int k)
{
	bool t=false;
	for(int i=0;i<s.size();i++)
	{
		if(s[i]=='\"')t=!t;
		if(i==k&&t)return true;
	}
	t=false;
	for(int i=0;i<s.size();i++)
	{
		if(s[i]=='\'')t=!t;
		if(i==k&&t)return true;
	}
	return false;
}
bool check(string s,int k)
{
	if(k==0||k==s.size()-1)return true;
	for(int i=0;i<17;i++)
	if(k>=x[i].size()&&s.substr(k-x[i].size(),x[i].size())==x[i])return false;
	if(s[k-1]==s[k+1]||incs(s,k))return false;
	if(d.find(s[k-1])!=string::npos||d.find(s[k+1])!=string::npos)return true;
	if(s[k-1]>='0'&&s[k-1]<='9')return true;
	if(s[k+1]>='0'&&s[k+1]<='9')return true;
	return false;
}
int main()
{
	cout<<"【代码风格转换器】\n此转换器适合 习惯大括号单独成行并且无多余空格和换行 的使用者\n\n";
	Sleep(1000);
	cout<<"请输入你要转换的代码（换行+Ctrl+Z结束）：\n";
	while(getline(cin,s))
	{
		if(s=="")continue;
		int k=0;
		while(s.find("",k)!=string::npos)k=s.find("",k),s[k]=' ',k++;
		k=0;
		while(s.find(" ",k)!=string::npos)
		{
			k=s.find(" ",k);
			if(check(s,k))s.erase(k,1);
			else k++;
		}
		for(int i=1;i<=cnt-1;i++)ans+="";
		if(s[0]=='}')
		{
			ans=ans+s+"\n",cnt--;
			continue;
		}
		if(cnt!=0)ans+="";
		if(s=="{")
		{
			ans=ans+s+"\n",cnt++;
			continue;
		}
		if(s[s.size()-1]=='{')
		{
			s.erase(s.size()-1),ans=ans+s+"\n";
			for(int i=1;i<=cnt;i++)ans+="";
			ans+="{\n";
			cnt++;
		}
		else ans=ans+s+"\n";
	}
	cout<<"这是转换后的代码：\n";
	Sleep(1000);
	cout<<ans;
	Sleep(1000);
	cout<<"\n\n按下任意键复制转换后的代码，如果不想复制请关闭窗口\n";
	system("pause");
	Copy(ans);
	cout<<"\n已复制，感谢使用代码风格转换器";
	return 0;
}
```

c++连点器

```cpp
#include<cstdio>
#include<windows.h>
#define KEY_DOWN(VK_NONAME) ((GetAsyncKeyState(VK_NONAME) & 0x8000) ? 1:0)
int main() {
	int now=0,k=0;
	printf("按1点击左键，按2停止\n");
	while(1) {
		if(KEY_DOWN('1')) {
			now=1;
			Sleep(100);
		}
		if(KEY_DOWN('2')) {
			now=0;
			Sleep(100);
		}
		if(now==1) {
			mouse_event(MOUSEEVENTF_LEFTDOWN,0,0,0,0);
			Sleep(1);
			mouse_event(MOUSEEVENTF_LEFTUP,0,0,0,0);
		}
		Sleep(1);
	}
	return 0;
}
```


剪切板管理器（自创）

```cpp
#include<bits/stdc++.h>
#include<windows.h>
using namespace std;

//互相对应的数组
const int N=1000000;
int copy_id[N+5];//剪切字符串的编号
string copy_str[N+5];//剪切字符串
bool have_num[N+5];

void Copy(string TempBin) {
	HGLOBAL hMemBin=NULL;
	PCHAR LockBin=NULL;
	OpenClipboard(NULL);
	EmptyClipboard();
	hMemBin=GlobalAlloc(GMEM_MOVEABLE,TempBin.size()+1);
	LockBin=(PCHAR)GlobalLock(hMemBin);
	RtlMoveMemory(LockBin,TempBin.c_str(),TempBin.size()+1);
	GlobalUnlock(hMemBin);
	LockBin=NULL;
	SetClipboardData(CF_TEXT,hMemBin);
	CloseClipboard();
}

void wait(double second) {//等待……秒
	Sleep(second*1000);
}

void go() { //数组初始化
	for(int i=1; i<=N; i++) {
		copy_id[i]=i;
	}
	for(int i=1; i<=N; i++) {
		have_num[i]=0;
	}
}

int start() { //开场白
	printf("欢迎来到剪切板！\n");
	wait(0.5);
	printf("本程序是为了解决用户当要复制多个内容时混乱的情况。\n");
	wait(0.5);
	printf("在这里，用户可以输入一串字符，系统会给予一个编号（字符串最大长度10^6，最多输入10^6个字符串）。\n");
	wait(0.5);
	printf("想要复制这串字符，只需输入这串字符的编号，这串字符就会自动复制到用户的剪切板中。\n");
	wait(1);
	printf("开始使用吧！！！\n");
	wait(1);
	system("pause");
	return 0;
}

void put_board() {//使用制表符输出剪切板
	for(int i=1; i<=1000000; i++) {
		if(have_num[i]==1) cout<<copy_id[i]<<'\t'<<copy_str[i]<<endl;
	}
	cout<<endl;
	return ;
}

void code_main() {
	go();
	start();
	while(1) {
		cout<<"如果您想增加内容，输入1；如果您想复制内容，输入2；如果您想退出程序，输入3。"<<endl;
		int tmp;
		cin>>tmp;
		if(tmp==1) {
			printf("请输入您要将字符串储存到剪切板中的哪一个位置（1-1000000之间的整数）：");
			int where;
			scanf("%d",&where);
			have_num[where]=1;
			printf("\n");

			printf("请输入您要储存到剪切板中的字符串（长度在1-1000000之间）：");
			string str;
			cin>>str;
			copy_str[where]=str;
			printf("\n");

			put_board();

			wait(5);
			system("pause");
		} else if(tmp==2) {
			printf("请输入您要复制第几个字符串（1-1000000之间的整数）：");
			int x;
			scanf("%d",&x);
			printf("\n");
			Copy(copy_str[x]);

			printf("\n");
			printf("内容已复制到剪切板！\n");
			system("pause");
		} else if(tmp==3){
			printf("再见！欢迎下次使用！\n");
			break;
		}
	}
	return;
}

int main() {
	code_main();
	return 0;
}
```

## 游戏类

[可编辑2048](https://hczhcz.github.io/my-2048/index.html?t=Ploblem+A&v2=log+n&v4=sqrt+n&v8=n&v16=n+log&v32=n+sqrt+n&v64=n%5E2&v128=n%5E2+log+n&v256=n%5E3&v512=n%5E4&v1024=2%5En&v2048=n%5En&m=Infinity&w=TLE&o=AC)

[【博弈论】信任的进化](https://dccxi.com/trust/)

[I WANNA](https://www.yikm.net/ib/index.html)

[军棋联机](https://www.luogu.com.cn/paste/onzki2vp)

[猜数](https://www.luogu.com.cn/paste/309ceohw)

[2048](https://www.luogu.com.cn/paste/o5w5gp1j)

[事件三子棋](https://www.luogu.com.cn/paste/ursic6dq)

[围棋](https://www.luogu.com.cn/paste/1qg4a1lh)

[C++控制台游戏（博客）](https://www.luogu.com.cn/blog/wuwendongxi/c-you-xi-suo-yin)

[谷歌小恐龙](chrome://dino/)

[Edge冲浪](edge://surf/)

[florr](https://florr.io/)

[digdig](https://digdig.io/)

[hole](https://hole.io/)

[generals](https://generals.io/)

[yorg](https://yorg.io/)

[poki](https://poki.cn/)

[iogames](https://iogames.space/)

[slay](https://slay.one/)

[物理画线](https://www.xiwnn.com/huaxian)

[普通2048](https://2048.io) | [OIer 2048](https://ak-ioi.com/apps/oi-2048/) | [时间复杂度2048](https://hczhcz.github.io/my-2048/index.html?t=Ploblem+A&v2=log+n&v4=sqrt+n&v8=n&v16=n+log&v32=n+sqrt+n&v64=n%5E2&v128=n%5E2+log+n&v256=n%5E3&v512=n%5E4&v1024=2%5En&v2048=n%5En&m=Infinity&w=TLE&o=AC) | [化学2048](https://dimit.me/Fe26/index_zh_CN.html)

[人生重开模拟器](https://liferestart.syaro.io/view/index.html)

[巨佬 InterN 编的游戏](http://aerfaying.com/Projects/815362)

[yumy](https://yumy.io/)

[4399](https://www.4399.com/)

[mc](https://mineparkour.club/)

[音游](https://cf.phicommunity.com.cn/)

[邪恶的2048](https://hotwords123.github.io/2048-evil/)

[大型2048](https://hotwords123.github.io/65536/)

[巨型2048](https://www.csie.ntu.edu.tw/~b01902112/9007199254740992/)

[博士2048](https://ymfa.github.io/phd-2048/?from=singlemessage&isappinstalled=0)

[1536](https://hotwords123.github.io/1536/)

[IAKIOI](https://ak-ioi.com/apps/oi-2048/)

[扫雷3D](https://www.revolversweeper.com/)

[太空公司](https://www.mhhf.com/game-5302/index.html)

[m28.studio（小游戏集）](https://m28.studio/)

[Hello Minecraft! Launcher](https://hmcl.huangyuhui.net/)

[高级小恐龙](https://dinoswords.gg/)

[名字竞技场](https://namerena.github.io/)

[yorg](https://yorg.io/)

[yorg3](https://yorg3.io/)

[小黑屋](https://www.xiaodao0.com/admin/index.html?lang=cn)

[C++游戏集](https://www.luogu.com.cn/blog/jvruo-0076/wow-hao-duo-c-you-hu-dai-ma-post)

[生命游戏](https://playgameoflife.com/)

[FC 游戏在线玩](http://lab.mkblog.cn/FCGames/#/)

[slay](https://slay.one/)

[信任的进化](https://dccxi.com/trust/)

[The Largest Collection of
Interactive Geometric
Puzzles](https://www.euclidea.xyz/)

[中国最大io游戏推荐网站](http://io233.com/)

[解谜](https://nazo.one-story.cn/)

[猫国建设者](https://likexia.gitee.io/cat-zh/#)

[国际象棋](https://www.chess.com/zh)

[膜拜Siyuan](https://lmoliver.github.io/mosiyuan/index.html)

[一个球？](https://www.revolversweeper.com/)

[HTML5游戏](https://blog.csdn.net/aaa333qwe/article/details/72879188)

[小游戏集（大）](https://xingye.me/game/index.php)

[sans](http://jcw87.github.io/c2-sans-fight/)

[人生重开模拟器](http://liferestart.syaro.io/public/index.html)

[generals](https://generals.io/)

[C++控制台游戏](https://www.luogu.com.cn/blog/wuwendongxi/c-you-xi-suo-yin)

[游戏](https://www.luogu.com.cn/discuss/416043)

[冲浪  （edge浏览器里打开）](edge://surf/)

[你画我猜](https://gartic.io/)

[bonk.io](https://bonk.io/)

[大游戏集](https://scorenga.com/url/a017-000/scor709/)

[大游戏集2](https://www.thegame.org/)

[大游戏集3](https://www.gamepix.com/?game=bowmasters&ppc=true&gclid=EAIaIQobChMI8sXkoJbj-AIVT0xgCh2cFACgEAEYASABEgJfJfD_BwE)

[大游戏集4](https://bihugames.com/gameshare/index.html?gclid=EAIaIQobChMIlZTakpfj-AIVFn2LCh0o_wsHEAEYASAAEgL15_D_BwE)


[大游戏集5](https://www.share-games.com/kids-games.htm?gclid=EAIaIQobChMIm8Lgx5fj-AIVp0PCBR1NxQHZEAEYASAAEgI1UPD_BwE)

[大游戏集6](https://www.crazygames.com/)

[io小游戏](https://www.luogu.com.cn/discuss/459837?page=2)

[io小游戏集](https://iogames.space/)

[MC（不是远古版本）](https://ws.imc.re/start.html)

[开挂人生](http://remake.solaking.com/)

[GitHub游戏](https://www.gityx.com/)

[florr](https://florr.io/)

[卡牌冒险者](http://cav.maougame.com/)

[卡牌冒险者2](http://cav2.maougame.com/)

[starblast](https://starblast.io/)

[YoHoHo](https://YoHoHO.io/)

[【投稿】构造【失效】](cnh5.gitee.io/structure)

[【投稿】协同放置（3000000玩家的超大型放置游戏）【失效】](synergism.g8hh.com)

[【投稿】无尽的饼干（v2.048）【失效】](orteil.dashnet.org/cookieclicker)

[文明放置2](https://g1tyx.github.io/cividlization2)

[创建你自己的世界（？](https://sandspiel.club/)

[神神子的hole.io](https://www.gamepix.com/play/hole-io#goog_slotcar_ad)

[c++游戏：王权](https://www.luogu.com.cn/paste/rsupsp43)

[Lotuses做的狼人杀](https://github.com/Lotuses-robot/Local_WolfmanKill)

[名字竞技场！](http://namerena.github.io/)

[数 学 作 图 题](https://www.euclidea.xyz/en/game/packs)

[进来练练你的手速！](http://www.rs100.cn/fun/fun.html)

[hacker模拟器](http://hackcode.ishoulu.com/scp/)

[florr.io](https://florr.io)

[物理画线](https://www.xiwnn.com/huaxian)

[围地大作战](https://www.gamepix.com/play/superhex-io)

[你 画 我 猜](https://gartic.io/)

[可以转动的魔方](https://huazhechen.gitee.io/cuber/)

[太空放置2](http://www.mhhf.com/gameps-5261)

[反应堆放置](https://likexia.gitee.io/reactoridle/)

[生火间](https://www.xd0.com/admin/index.html?lang=cn)

[Chrome小恐龙](chrome://dino/)

[把猫猫围起来](https://luogulo.gq/show.php?url=https://www.luogu.com.cn/discuss/362595?page=15)

[sansfight](https://jcw87.github.io/c2-sans-fight/)

[对诗词（用括号把对的字替代掉哦）](http://poem.rotriw.com/)

[generals.io将军棋](https://generals.io)

[洛谷树](https://www.luogu.com.cn/problem/T230828)

[脆皮（？](https://yx.g8hh.com/cuipi/)

[OI版你画我猜](https://gartic.io/4614RH)

[机 房 惨 案 模 拟 器](https://www.ccw.site/detail/6242dd0e11d5e716cc30ac1a?SubjectAreaGroupId=3&component=0&inviteCode=4ODead8DgbyENEcZ&module=0)

[打字游戏XD](https://zty.pe)

[yorg.io](https://yorg.io)

[可以联机的狼人杀（](https://twt-tec.github.io/)

[slay.one](https://slay.one/)

[AKIOI之路](https://www.luogu.com.cn/blog/seac/tui-fei-ji-lu-ak-ioi)

[找 牛](https://findtheinvisiblecow.com/)

[Flappy Bird飞扬的小鸟](http://flappybird.io/)

[地下探险队](http://ta.maougame.com/)

[卡牌冒险者](http://cav.maougame.com/)

[卡牌冒险者2](http://cav2.maougme.com/)

[塔防|扫雷|棋类等](https://www.tafang123.com/)

[神神子的deeeep.io](https://deeeep.io/?utm_source=w.shadiao.app)

[krunker大型像素枪战](https://krunker.io)

[贪吃陀螺](http://spinz.io/)

[shapez 放置](https://shapez.io/)

[吃鸡](http://surviv.io/)

[超级玛丽奥](http://taomi.com/)

[海盗大逃杀](https://yohoho.io/)

[digdig.io](https://digdig.io/)

[信任的进化](https://sekai.co/trust/)

[立体扫雷](https://www.revolversweeper.com/)

[流浪日记](http://www.399.com/flash/193490_1.htm)

[MC_1.0](https://classic.minecraft.net/)

[在线下棋](https://www.chess.com/zh)

[网页版dino](http://chromedino.com/)

[仿generals小游戏](https://kana.byha.top:444/)

[海战棋网页版](http://zh.battleship-game.org/)

[五子棋](http://html5.huceo.com/wzq/)

[无尽进度条](http://likexia.gitee.io/progress-quest/main.html#Iexkrack)

[钢琴模拟器](https://www.xiwnn.com/piano/)

[小小的解密游戏](https://nazo.one-story.cn/)

WORDLE GAMES:[猜单词](https://wordlegame.org/) / [猜单词，不过是中文版](https://handle.antfu.me/) / [猜单词，不过是猜数字](https://numberle.org/) / [猜单词，不过是两个一起猜](https://dordlewordle.com/) / [猜单词，不过是四个一起猜](https://quordlewordle.com/) / [猜单词，不过是八个一起猜](https://octordlewordle.org/) / [猜单词，不过是猜音符](https://medle.akashiya.top/)

猫国建设者同源游戏：[【已失效】进化](https://likexia.gitee.io/evolve/) / [猫国建设者](https://likexia.gitee.io/cat-zh/#) / [猫国建设者的作弊码XD](http://bbs.gityx.com/forum.php?mod=viewthread&tid=32)

2048游戏：[三体2048](https://cyberzhg.github.io/2048/skin_santi.html) / 
[时间复杂度 2048](https://hczhcz.github.io/my-2048/index.html?t=Ploblem+A&v2=log+n&v4=sqrt+n&v8=n&v16=n+log&v32=n+sqrt+n&v64=n%5E2&v128=n%5E2+log+n&v256=n%5E3&v512=n%5E4&v1024=2%5En&v2048=n%5En&m=Infinity&w=TLE&o=AC) / [化学2048](https://dimit.me/Fe26/index_zh_CN.html) / [OIER's 2048](https://ak-ioi.com/apps/oi-2048/) / [普普通通的2048](https://cn.newdoku.com/2048.php) / [朝代2048](http://www.oprilzeng.com/2048/)

人生重开游戏们：[人生重开普通版](https://liferestart.syaro.io/view/index.html) / [人生重开开挂版本](http://restart.sshh.top/view/) / [人生重开天命版(手机不能玩)](http://restart.typekuon.com/lifeRestart/view/) / [人生重开人上人版本](https://service-anw3da5k-1251676728.gz.apigw.tencentcs.com/release/view/index.html) / [人生重开爆改版(手机不能玩)](http://remake.solaking.com/)

游戏合集入口：[微伞小游戏](http://www.wesane.com/) / [T神游戏集](https://www.luogu.com.cn/blog/z1e2k3i4/) / [c++游戏整合](https://www.luogu.com.cn/blog/wuwendongxi/c-you-xi-suo-yin) / [gamepix.com全是io游戏！](https://www.gamepix.com/?ppc=true&gclid=EAIaIQobChMIoZKtzuy28wIVhoKWCh3hVgXnEAEYASAAEgIHUfD_BwE) /[颓废用的io games](https://www.luogu.com.cn/discuss/show/60255) / [iogames网站](https://iogames.space/) / [游戏合集](https://www.luogu.com.cn/blog/wuwendongxi/wang-ye-you-xi) / [IO233（IO游戏集合）](http://io233.com/) / [yikm.net（单机闯关打类游戏）](https://www.yikm.net/#www.xd0.com) / [单机创意类游戏](https://game.fm/arcade-category/utm-game36/) / [xingye小游戏合集](https://xingye.me/game/index.php) / [【投稿】各种放置游戏大全](g8hh.com) / [【投稿】各种放置游戏大全2](gityx.com)


# 杂项

[某科学的超电磁炮格式同款生成器](http://to-a.ru/)

[在线PS（亲测没用](https://ps.88id.com/)

[麦块成就生成器](http://mc.whitegem.net/)

[首字母缩写查找器](https://lab.magiconch.com/nbnhhsh/)

[梯子](https://arr003.network/download/)

[【已失效】从洛谷博客导入功能上线：OIer Space 更新！](https://www.luogu.com.cn/discuss/418739)

[OIer Space](https://oier.space/)

[摸鱼器](https://www.luogu.com.cn/discuss/423833)

[DeepL翻译——不是生草机！](https://www.deepl.com/translator)

[一个小工具箱](http://www.atoolbox.net/)

[base64编码/解码转换](https://tool.ip138.com/base64/) [+1](https://base64.us/)

[放大图片工具](https://bigjpg.com/zh)

[生成二次元头像工具](https://waifulabs.com/)

[测试密码强度器](https://www.passwordmonster.com/)

[数字114514化工具](https://lab.magiconch.com/homo/)

$\texttt{{\color{8E44AD}图床}}$：[洛谷图床](https://www.luogu.com.cn/paste) / [Imgbb图床](https://imgbb.com/) / [Superbed图床](https://www.superbed.cn/) / [Imgtu图床](https://imgtu.com/)

# 脚本

[洛谷私信删除脚本](https://www.luogu.com.cn/paste/02vm3moy)|
[洛谷删犇器（悲](https://www.luogu.com.cn/blog/firestar/post-zi-dong-shan-chu-qi)
[练习情况题目显示颜色](https://greasyfork.org/zh-CN/scripts/392036-%E6%B4%9B%E8%B0%B7%E9%A2%98%E7%9B%AE%E9%9A%BE%E5%BA%A6%E6%98%BE%E7%A4%BA-luogu-dif-render)

[【脚本】Luogu Search AnyWhere By tiger2005](https://www.luogu.com.cn/paste/9iot1dql)

[洛谷主页背景](https://www.luogu.com.cn/blog/liutianyou/Luogu-Background)

$\texttt{{\color{8E44AD}exlg}}$：[exlg下载地址](https://exlg.cc/index.html) | [exlg说明书QWQWQWQ](https://www.luogu.com.cn/blog/hello----world/mei-hua-luo-gu) | [专贴](https://www.luogu.com.cn/discuss/432028) | [6.6.0 无法显示解决方法](https://www.luogu.com.cn/blog/Sunny-mailbox/exlg-zui-xin-ban-ben-bug-xiu-fu) [图解版](https://www.luogu.com.cn/paste/cwwgk7we)

# 做题

x倍经验：[六倍经验](https://www.luogu.com.cn/discuss/237341)|[九倍经验](https://www.luogu.com.cn/discuss/167756)|[N倍经验](https://www.luogu.com.cn/training/325140#problems)|[六倍经验*2](https://www.luogu.com.cn/discuss/740600)

[最水紫题](https://www.luogu.com.cn/training/118978#information)

计算器：[geogebra图形计算器](https://www.geogebra.org/)|[demos图形计算器](https://www.desmos.com/calculator)

综合题单​：[StudyingFather的洛谷综合题单](https://studyingfather.com/archives/841)|[SPFA的试炼场](https://www.luogu.com.cn/paste/xbql0gp4)

[质数查找和检验](https://zh.numberempire.com/primenumbers.php)

[文本比较器](https://www.diffchecker.com/)

[graph_editor图论画图工具](https://csacademy.com/app/graph_editor/)

[八聚氧 吸到你爽](https://www.luogu.com.cn/paste/uty2joq9)

[SUPER 快读](https://www.luogu.com.cn/paste/ilt13pl4)

# 有用的网站

- [学习历史的好东西](https://www.britannica.com/)
- [背景图搜索站](https://wallhaven.cc/)
- [OIERdb](https://bytew.net/OIer/)
- [排序图像化网站](https://visualgo.net/zh)
- [IOI官网](https://ioinformatics.org/)
- [Google 全景地图 qwq](http://www.gditu.net/)
- [冬日绘版入口](https://www.luogu.com.cn/paintboard)
- [犇 犇 龙 王 榜](https://bens.rotriw.com/)
- [c++百科全书](https://zh.cppreference.com/w/?tdsourcetag=s_pcqq_aiomsg)
- [byvoid.com](https://byvoid.com/)
- [哔哩哔哩](https://www.bilibili.com)
- [孟坤lab实验室](http://lab.mkblog.cn/)
- [hackchat](https://www.luogu.com.cn/discuss/60199) [他的指令](https://tieba.baidu.com/p/6833224084)
- [解决数学问题的好帮手wolframalpha](https://www.wolframalpha.com/)
- [百度](https://www.baidu.com/)
- [百度翻译](https://fanyi.baidu.com/)
- [百度百科](https://baike.baidu.com/)
- [萌娘百科](https://zh.moegirl.org.cn/Mainpage) / [日文版-萌えっ娘百科事典](https://ja.moegirl.org.cn/Mainpage) / [英文版-Moegirlpedia](https://en.moegirl.org.cn/Mainpage)
- [伪基百科](https://en.uncyclopedia.co/wiki/Main_Page)
- [MCMOD百科](https://www.mcmod.cn/)
- [SCP百科](https://scp-wiki.wikidot.com/)
- [樱花动漫！！！]()
- [OI-wiki](https://oi-wiki.org/)
- [MC wiki](https://minecraft.fandom.com/zh/wiki/Minecraft_Wiki)
- [原神wiki](https://genshin-impact.fandom.com/zh/wiki/%E5%8E%9F%E7%A5%9E_Wiki)
- [洛谷](https://www.luogu.com.cn/)
- [Libre OJ](https://loj.ac/)
- [Hydro OJ](https://hydro.ac/)
- [JZOJ](http://www.jzoj.cn/)
- [CF](https://codeforces.com)
- [VJUDGE镜像](https://vjudge.csgrandeur.cn/)
- [万能头包含什么？](https://www.luogu.com.cn/paste/7kp15vr9)

# 资料

[OI大纲](https://www.luogu.com.cn/paste/sha10y1m)   
[Eason_AC 的 OI 小技巧](https://www.luogu.com.cn/paste/2dlbe6bi)   
[如何选择笔记本电脑？](https://www.luogu.com.cn/blog/dbyblog/post-bi-ji-ben-tui-jian)   
[破解防沉迷NB](https://hydro.ac/d/arkoi/discuss/61309ef564197708923a7c77#1632142737686)   
[临时抱CCF脚 ~~被CCF踢一脚~~ CSP初赛知识点梳理](https://www.luogu.com.cn/blog/334586/csp-pre-knowledge)   
[RE：从零开始搭建自己的博客](https://www.luogu.com.cn/blog/12cow/wordpress)   
[CF使用手册](https://zhuanlan.zhihu.com/p/42106537)   
[准备AFO的小盆友看这里](https://littlered.blog.luogu.org/ru-he-you-ya-di-hu-jing-sai-fen-shou)   
[c++真的是四舍五入吗! StudyingFather亲授](https://www.luogu.com.cn/paste/elevjscq)   
[StudyingFather的题解小妙招](https://studyingfather.blog.luogu.org/blog-written-guide)   
[B站视频插入方式](https://www.luogu.com.cn/paste/l9faoe0v)   
[KMP学习笔记](http://www.matrix67.com/blog/archives/115)   
[洛谷词典](https://www.luogu.com.cn/blog/FCBM71/luogu-dictionary) [+1](https://www.luogu.com.cn/blog/WARNING/luo-gu-ding-lv-ming-ci) [+2](https://www.luogu.com.cn/paste/rnljplko) [+3](https://www.luogu.com.cn/blog/334586/luogu-dictionary)   
[【已失效】个人主页常用技巧](https://wls.blog.luogu.org/ge-ren-zhu-ye-chang-yong-ji-qiao)   
[打表日报](https://www.luogu.com.cn/blog/2-6-5-3-5/guan-yu-da-biao)   
[qq表情以及缩写](https://studyingfather.blog.luogu.org/qq-stickers)   
[如何做出一个好的PPT？](https://www.luogu.com.cn/blog/lijiaan/how-to-make-ppt)   
[如何使用Markdown？](https://www.luogu.com.cn/blog/luogu/how-to-use-markdown)   
[洛谷官方的 Latex 说明](https://www.luogu.com.cn/blog/luogu/latex)   
[Latex 数学公式大全](https://www.luogu.com.cn/blog/IowaBattleship/latex-gong-shi-tai-quan)   
[Latex 入门](https://www.luogu.com.cn/blog/IowaBattleship/latex-ru-men)   
[Katex公式大全](https://www.luogu.com.cn/paste/hs3jg81l)   
[咕值介绍](https://www.luogu.com.cn/discuss/show/83952)   
[二进制与位运算](https://www.luogu.com.cn/blog/chengni5673/er-jin-zhi-yu-wei-yun-suan)   
[vijos的骗分导论（？](https://vijos.org/discuss/5343eb6c48c5fc86468b457d)   
[command_block的博客目录（干货）](https://www.luogu.com.cn/blog/command-block/blog-suo-yin-zhi-ding-post)   
[洛谷常见问题 BY Elgo87](https://www.luogu.com.cn/blog/393864/post-luo-gu-chang-jian-wen-ti)   
[c++如何存档与读档？](https://blog.csdn.net/m0_46145704/article/details/106984276)   
[没有exlg，如何使用这些表情？](https://www.luogu.com.cn/paste/7oarm3bz)   
[EasyX的介绍](https://xiao-l.blog.luogu.org/EasyX)   
[EGE 库入门](https://www.luogu.com.cn/blog/ixRic/ege-flappy-bird)   
[Microsoft edge 安装 tarpermonkey 出错怎么办？](https://blog.csdn.net/qq_61901005/article/details/123554971)   
[CF快速入门](https://www.luogu.com.cn/blog/ezoixx130/codeforces-advanced-tutorial)   
[隐私已死](https://www.luogu.com.cn/blog/NaCl7/Privacy-is-dead)   
[骗分导论（blog](https://www.luogu.com.cn/blog/LinearExpectation/method-to-get-score-in-a-easy-way)   
[复赛时要记住的 30 句话](https://www.luogu.com.cn/blog/zyf2004/fu-sai-shi-yao-ji-zhu-di-30-gou-hua)   
[高中数学全讲](https://www.luogu.com.cn/blog/Shuchong/#type=%E9%AB%98%E4%B8%AD%E6%95%B0%E5%AD%A6)   
[**某些有用的链接**](https://www.luogu.com.cn/blog/ltzlInstallBl/sajdkljsaldjsalkjdlksa)   
[公告整合【新】](https://www.luogu.com.cn/discuss/441670)   
[【搬运】高中数学笔记整理](https://www.luogu.com.cn/blog/hugocaicai/gao-zhong-shuo-xue-xue-xi-bi-ji)   

# 摸鱼

[【投稿】Netherite_ingot 的剪切板解密](https://www.luogu.com.cn/paste/px27wryo)

[我们至今仍未知道那天在省选看到的没落的强省强校校队究竟有没有崛起](https://www.luogu.com.cn/blog/578029/wo-men-zhi-jin-reng-wei-zhi-dao-nei-tian-zai-xing-xuan-kan-dao-di-mei-post)

[generals实用技巧](https://www.luogu.com.cn/blog/A-Dark-Horcrux/kana-zong-ling-kai-shi-di-yi-shi-xun-lian)

[机房欢迎你~【失效】](https://www.luogu.com.cn/blog/cjnFreedomKingblog/welcome-to-jifang)

[小鸡子，露出黑脚了吧【貌似失效】](https://alpha1022.img.ihcr.top/cxk.jpg)

[Minecraft世界观](https://www.luogu.com.cn/paste/1i899qaa)

[对称作画](http://weavesilk.com/)

[奇奇怪怪的洛谷题目整合](https://www.luogu.com.cn/blog/just-like-you--break/post-xin-noip-zhen-xiao-ju-wen-ti-di-bian-hua)

[1-100的114514化](https://www.luogu.com.cn/paste/r08ov4wu)

[划动鼠标来出现图片](https://www.koalastothemax.com/?aHR0cHM6Ly9jZG4ubHVvZ3UuY29tLmNuL3VwbG9hZC9pbWFnZV9ob3N0aW5nL3phbWl4dGZvLnBuZw==)

[StudyingFather的2021冬日绘版实时报道](https://www.luogu.com.cn/paste/3om04dvb)

[Inkyo的洛谷冬日绘版战地记者计划](https://www.luogu.com.cn/blog/266011/post-dong-ri-hui-ban-zhan-di-ji-zhe-ji-hua) [+2021年冬日绘版报道](https://www.luogu.com.cn/paste/co3ue42e)

[OI之歌（汇总版）](https://www.luogu.com.cn/blog/Ynoi/oi-ge)

[cz的直播间](https://live.bilibili.com/17143)

[兔队的直播间](https://live.bilibili.com/9378049)

[考古指南](https://www.luogu.com.cn/paste/gi01rkt9)

[语文课本课文《做干净的奥赛》](https://www.luogu.com.cn/paste/02v63s10)

[典例 BY 小糯米](https://www.luogu.com.cn/blog/masterfufufu/example)

[家长直呼太暴力！这些算法或将被从考纲删除（完整版）](https://www.luogu.com.cn/paste/8hl67294)

[段子们](https://www.luogu.com.cn/blog/195331/ge-zhong-geng) [+1](https://www.luogu.com.cn/paste/l2kg4x6e) [+2](https://www.luogu.com.cn/paste/xuiwchzr) [+3](https://www.luogu.com.cn/blog/373293/funnythings) [+4](https://www.luogu.com.cn/paste/vsuoda3x) [+5](https://www.luogu.com.cn/paste/tmztr4mg) [+6](https://www.luogu.com.cn/paste/s5soypjp)

[Google生草（cz亲测](https://www.luogu.com.cn/blog/chen-zhe/ba-luo-gu-she-ou-gui-ze-fan-yi-20-bian)

[离散小波变换°の主页](https://www.luogu.com.cn/paste/ejpwsu2g)

[偷袭被选入语文课本啦！（？）](https://www.luogu.com.cn/blog/TRUE3494/yu-wen-zao-du-cai-liao-di-yi-ke-tou-xi-post)

[kkk爆照啦（？）](https://www.bilibili.com/video/av13239644?from=search&seid=967135848787573054)

[人 win 浅谈 npy 的好处](https://www.cnblogs.com/lnzwz/p/14382308.html)

[洛谷|最大青少年感情交流中心（咕民情感帖收录）](https://www.luogu.com.cn/paste/2gvwjfjv)

[阿伟：我的SPFA被卡了啊啊啊啊啊啊](https://www.luogu.com.cn/paste/bzsaavcv)

[愚人节JC指南(?)](https://www.luogu.com.cn/discuss/show/308021)

[又是一个宝藏帖子](https://www.luogu.com.cn/discuss/66031)

[ACG台词 合集](https://zh.moegirl.org.cn/Template:ACG%E7%BB%8F%E5%85%B8%E5%8F%B0%E8%AF%8D)

[CSP2021游记整合贴](https://www.luogu.com.cn/discuss/370496)

[CSP2022游记整合贴](https://www.luogu.com.cn/discuss/521014)

[洛谷之光 BY 小糯米](https://www.luogu.com.cn/blog/masterfufufu/catalog)

[お 姉 さ ま ！ ！ ！](https://zh.moegirl.org.cn/%E5%BE%A1%E5%9D%82%E7%BE%8E%E7%90%B4)

[洛谷工坊游记--管理员的日常](https://www.luogu.com.cn/blog/12cow/luo-gu-gong-fang)

[Harry Potter的各类咒语合集](https://www.luogu.com.cn/paste/ccwafoje)

[文文新闻1.0目录](https://www.luogu.com.cn/blog/Edward-Elric/wen-wen-xin-wen-mu-lu)

[文文新闻2.0目录](https://www.luogu.com.cn/paste/7rmu8xyr)

[在洛谷，你甚至可以观看 Dream](https://www.luogu.com.cn/paste/wb2dafwq)

[StudyingFather的小说](https://loj.ac/d/3065)

[Tokyo 2020专用讨论帖](https://www.luogu.com.cn/discuss/show/190840)

[考古！史上最早帖子](https://www.luogu.com.cn/discuss/show/5)

[如何用代码表白？](https://blog.csdn.net/weixin_50915462/article/details/113805008?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522164483295216780271545017%2522%252C%2522scm%2522%253A%252220140713.130102334..%2522%257D&request_id=164483295216780271545017&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~top_positive~default-1-113805008.first_rank_v2_pc_rank_v29&utm_term=%E6%83%85%E4%BA%BA%E8%8A%82%E8%A1%A8%E7%99%BD%E4%BB%A3%E7%A0%81&spm=1018.2226.3001.4187)

[考古时应该注意的一些事情](https://www.luogu.com.cn/paste/gozs434b)

[洛谷电视台.jpg](https://www.luogu.com.cn/team/7773)

[明日之後 的小说](https://www.luogu.com.cn/blog/mingrizhihou/wo-ye-fou-zhi-dao-xie-shi-me-biao-ti-di-kai-pian-ci)

$\texttt{{\color{8E44AD}迷惑代码合集}}$：[迷惑代码合集](https://www.luogu.com.cn/paste/uutz1v8f)/[CSP2021迷惑代码合集](https://www.luogu.com.cn/paste/7jqj2ud8)/[上海 CSP-S 组奇葩代码合集](https://www.luogu.com.cn/blog/chen-zhe/shang-hai-csp-s-zu-ji-pa-dai-ma-ge-ji)/[cz的A+B题解](https://www.luogu.com.cn/blog/chen-zhe/p1001-ab-problem)/[NOIP2021代码合集](https://www.luogu.com.cn/blog/andrew-zhong/2021noip)/[对不起这里才是NOIP2021代码合集](https://www.luogu.com.cn/paste/g6v4kb5q)

$\texttt{{\color{8E44AD}神贴们}}$：[关于CCF检查代码中是否存在影响CCF名誉的词汇并传唤选手此事的看法:)](https://www.luogu.com.cn/discuss/386210) / [AKCSP的最佳方式](https://www.luogu.com.cn/discuss/372823) / [AKCSP的最佳方式 续集XD](https://www.luogu.com.cn/discuss/373449) / [lxl很可怜不要欺负他](https://www.luogu.com.cn/discuss/362595) [进不去？来这](https://luogulo.gq/show.php?url=https://www.luogu.com.cn/discuss/362595) / [U K E](https://www.luogu.com.cn/discuss/show/61884) / [U K E 二 世](https://www.luogu.com.cn/discuss/show/347128) / [U K E 二 世 语 录](https://www.luogu.com.cn/paste/xmp7eg4n) / [U K E 二 世 t q l % % %](https://www.luogu.com.cn/paste/jiatdfqq) / [U K E 二 世 t q l % % % 2](https://www.luogu.com.cn/paste/t8dh4v7g) / [wangyibo201026の名言金句](https://www.luogu.com.cn/paste/6m2g65w2) / [神奇のOJ](https://www.luogu.com.cn/discuss/show/251698) / [whk大佬](https://www.luogu.com.cn/discuss/show/294919) / [~~《两只老虎》~~](https://www.luogu.com.cn/discuss/show/200400) / [迫真大型连续剧《Karry5307：从天上到地下》](https://www.luogu.com.cn/blog/WYXkk/the-chronicle-of-karry5307) / [神贴全在这里](https://arachnidaqueen.blog.luogu.org/nei-suo-nian-di-shen-tie-shou-lu) [+1](https://www.luogu.com.cn/blog/FCBM71/luo-gu-shen-tie-ji-ge-chi-xu-geng-xin-post) / [**自 投 罗 网**](https://luogulo.gq/show.php?url=https://www.luogu.com.cn/discuss/423258) / [《上海洛谷网络科技有限公司会在3年内IPO》](https://www.luogu.com.cn/discuss/208548) / [奇奇怪怪的敏感词检测](https://www.luogu.com.cn/discuss/396597)

# 测试

[快点来自测自己是哪个学院哒](https://wizard-tool.com/tests.html)

[荣格认知功能测试【标准版】](https://www.jungus.cn/zh-hans/test/Standard)

[荣格认知功能测试【专业版】](https://www.jungus.cn/zh-hans/test/Standard)

[感谢，又有人格测试机](https://www.16personalities.com/ch/)

[NFC性格测试](http://www.apesk.com/p/index.asp?mq=&re=yes)

[主义测试器](https://yavt.fengtao.xyz/)

[词汇量测试](https://preply.com/en/learn/english/test-your-vocab)

[你是英语几级？](https://preply.com/en/language-tests/english)

[又是一个英语级别测试](https://www.efset.org/zh/)



## 题解专用

[巨佬 metaphysis 写的书](https://blog.csdn.net/metaphysis/article/details/90288252)

[数字帝国](https://zh.numberempire.com/)

[\LaTeX 数学公式大全](https://www.luogu.com.cn/blog/IowaBattleship/latex-gong-shi-tai-quan)

[图形计算器](https://www.desmos.com/calculator?lang=zh-CN)

[Virtual Judge](https://vjudge.net/)

[NB物理实验](https://wl.nobook.com/index.html#/console/templates)

[NB化学实验](https://huaxue.nobook.com/index.html#/chemical/new)

[NB生物实验](https://czsw.nobook.com/index.html#/console/templates)

[wolframalpha](https://www.wolframalpha.com/)

[图论](https://csacademy.com/app/graph_editor/)

[OI WIKI](https://oi-wiki.org/)

[oeis](https://oeis.org/)

[工具箱](https://www.luogu.com.cn/paste/yisybkqs)

[信息学](http://xn--vuqs4zq3d.com/)

[压行！](https://mivik.gitee.io/compress)

[试炼场](https://www.luogu.com.cn/paste/pk0q3rw8)

[骗分导论](https://www.luogu.com.cn/paste/4m9bwodc)

[CSP初赛知识点梳理](https://www.luogu.com.cn/blog/334586/csp-pre-knowledge)

[洛谷日报](https://www.craft.do/s/N0l80k2gv46Psq) 

[数学画图](https://www.geogebra.org/)

[自动AC机](https://blog.csdn.net/weixin_43762849/article/details/91456874?spm=1001.2101.3001.6650.1&utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7ECTRLIST%7Edefault-1.highlightwordscore&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7ECTRLIST%7Edefault-1.highlightwordscore)

[函数图像绘制器](http://www.fooplot.com/#W3sidHlwZSI6MCwiZXEiOiJ4XjIiLCJjb2xvciI6IiMwMDAwMDAifSx7InR5cGUiOjEwMDB9XQ--)

[手画数学公式转 $\LaTeX$](https://webdemo.myscript.com/)

[模板](https://www.luogu.com.cn/paste/4ep52wjf)

[$\LaTeX$](http://www.mohu.org/info/lshort-cn.pdf)

[OISO](https://www.oiso.cf/)

[字符画](https://www.fontke.com/tool/image2ascii/)

[font](https://cn.piliapp.com/instagram/fonts)

[WindowsXP](https://geekprank.com/)

[bilibili](https://www.bilibili.com/)

[洛谷日爆检测器](https://luogu-status.d0j1a1701.cc/)

[营销号生成器](https://codepen.io/kasei-dis/full/JjYjwza)

[手速](https://makysdd.github.io/)

[摸鱼导论](https://www.luogu.com.cn/blog/101117dcx/post-mo-yu-dao-lun-geng-xin-post)

[文字反转](https://www.upsidedowntext.com/)

[奇怪的缩写](https://www.luogu.com.cn/discuss/91268)

[出现幻觉](https://strobe.cool/)

[MC WIKI](https://minecraft.fandom.com/zh/wiki/Minecraft_Wiki)

[卡牌生成](http://lyciumaker.com/)

[鼠标指针](https://zhutix.com/tag/cursors/)

[洛谷词典](https://www.luogu.com.cn/blog/334586/luogu-dictionary)

[黑客打字器](http://hackcode.ishoulu.com/linux/)

[百度一下](https://baidu.physton.com/?q=%E7%99%BE%E5%BA%A6)

[洛谷神贴集合](https://www.luogu.com.cn/blog/FCBM71/luo-gu-shen-tie-ji-ge-chi-xu-geng-xin-post)

[恶臭数字](https://lab.magiconch.com/homo/)

[艺术家](http://weavesilk.com/)

[上当空间](http://www.rs100.cn/fun/fun.html)

[镜子网站](http://lab.mkblog.cn/mirror/mirror.html?url=http%3A%2F%2Fwww.luogu.com.cn/user/536743)

[JC](https://www.luogu.com.cn/blog/19ty84/lun-jc)

[迫真大型连续剧《Karry5307：从天上到地下……？》](https://www.luogu.com.cn/blog/WYXkk/the-chronicle-of-karry5307)

[表情](https://www.luogu.com.cn/paste/nm8j6ss6)

[连点器](https://www.luogu.com.cn/paste/87ms4nd1)

[锰洛谷](https://www.luogu.com.cn/discuss/449023)

[洛谷定律及名词](https://www.luogu.com.cn/blog/WARNING/luo-gu-ding-lv-ming-ci)

[碳洛谷](https://www.luogu.com.cn/paste/c8wb3geg)

[洛谷小说馆](https://www.luogu.com.cn/discuss/66031)

[笑死图](https://www.zhihu.com/question/449542337)

[鲁迅](luogu.com.cn/discuss/65945)

[洛谷钩子](https://www.luogu.com.cn/paste/6naul3b3)

[随机验证码](https://www.luogu.com.cn/api/verify/captcha)

[计数器](https://www.hit-counts.com) 

[氙洛谷](https://greasyfork.org/scripts/433471)

[深色模式插件下载](https://www.luogu.com.cn/paste/s03jmqsz)

[洛谷界面优化器](https://exlg.cc//install.html) 

[一些好van的生成器](https://zhuanlan.zhihu.com/p/374071641)

[洛谷新手指南](https://www.luogu.com.cn/paste/2ozzdnfr)

[免费生成语录字体图片](https://www.qqxiuzi.cn/ziti/fzjljt/)

[洛谷个人名片生成](http://luogu.wao3.cn/) 

[刷屏神器](https://www.luogu.com.cn/paste/fvddyhi0) 

[假装系统更新](https://fakeupdate.net/) 

[测试手速](https://www.arealme.com/apm-actions-per-minute-test/zh/?ag)

[孟坤实验室](http://lab.mkblog.cn/)

[代码块的神奇用法](https://www.luogu.com.cn/discuss/165653)

[洛谷聊天室](https://hack.chat/?LuoGu_Online_Chat_Room)

[测试你的密码防JC能力](https://www.passwordmonster.com/) 

[美化洛谷](https://www.luogu.com.cn/blog/hello----world/mei-hua-luo-gu)

[ejectamenta](https://ejectamenta.com/)

[flagcounter](https://flagcounter.me/)

[不可以，总司令](https://www.luogu.com.cn/paste/bdru5vp4)

## 学术专用

[silk](http://weavesilk.com/)  

[图床1](https://imgtu.com/)  

[图床2](https://imgurl.org)  

[新大陆](https://www.zhihu.com/question/293309623/answer/825659532)  

[OIerDb](https://bytew.net/OIer/)  

[鼠标指针](https://zhutix.com/tag/cursors/page/2/)  

[数学工具](https://www.desmos.com)  

[emo合成](https://tikolu.net/emojimix/)  

[JiYuTrainer](https://des0402.lanzoui.com/inUI9iuu1rg) 

[Editor(画图)](https://csacademy.com/app/graph_editor/) 

[制作思维导图](https://gitmind.cn/)  

[$\LaTeX$公式大全](http://www.mohu.org/info/symbols/symbols.htm)  

[天体运行模拟器](https://cybermap.kaspersky.com/cn/)  

[在线音频格式转换](https://www.aconvert.com/cn/audio/) 

[LaTex数学公式大全](https://www.luogu.com.cn/blog/IowaBattleship/latex-gong-shi-tai-quan)  

[狗屁不通文章生成器](https://suulnnka.github.io/BullshitGenerator/index.html)  

[注册SPOJ（不用科学上网）](https://www.luogu.com.cn/paste/jq3nlpwu)  

[学习笔记](https://www.luogu.com.cn/blog/windblow/xue-xi-bi-ji-ji-ge)  

[$\LaTeX$ 公式大全](https://www.luogu.com.cn/blog/IowaBattleship/latex-gong-shi-tai-quan) 

[刷题必备](https://www.luogu.com.cn/paste/no9hab5n)  

[在线$\LaTeX$编辑工具](https://www.codecogs.com/latex/eqneditor.php?lang=zh-cn) 

[another version](https://www.latexlive.com/)  

[C++ reference](https://zh.cppreference.com) 

[cplusplus](https://www.cplusplus.com) 

[OIwiki](https://oi-wiki.org/)  

[画图(图论)](https://csacademy.com/app/graph_editor/) [镜像](https://riverhamster.gitee.io/app/graph_editor/)  

[OIer网址大全](https://tools.oiclub.top/)  

[随机美图](https://www.loliapi.com/acg/)  

[随机图床](https://imgapi.xl0408.top/index.php) 

[分类美图](https://img.moehu.org)  

[$\LaTeX$公式大全](https://www.luogu.com.cn/blog/IowaBattleship/latex-gong-shi-tai-quan)  

[刷题必备](https://www.luogu.com.cn/paste/no9hab5n)  

[在线$\LaTeX$编辑工具](https://www.codecogs.com/latex/eqneditor.php?lang=zh-cn)  

[能发题解的水题](https://www.luogu.com.cn/training/264168#problems)  

[小黑屋](https://www.xd0.com/admin/index.html?lang=cn)  

[名字竞技场](http://namerena.github.io/)  

[随机无用网站](https://theuselessweb.com/) 

[奇怪网站收藏](https://fuun.fun/)  

[C++连点器](https://www.luogu.com.cn/paste/sn09ee6u)  

[出了神贴的神仙题](https://www.luogu.com.cn/training/3504#information) 

[欧亨利结局的小故事](https://www.zhihu.com/question/322478979)

[洛谷卡片](https://blog.jerryz.com.cn/article/Luogu-User-Card/)

[一个云剪切板](https://www.luogu.com.cn/paste/m3hp6kgh)  

[东方狗下载站](https://cloud.lilywhite.cc/s/4ZUW?path=%2F) 

[神奇海螺试验场](https://lab.magiconch.com/)  

[能不能好好说话？](https://lab.magiconch.com/nbnhhsh/) 

[恶臭数字论证器](https://lab.magiconch.com/homo/)  

# 一些奇奇怪怪的东西

```
                                                         
                                                        顶顶顶顶
                                                顶顶顶顶顶顶顶顶顶
                                    顶顶顶顶顶顶顶顶顶顶顶顶顶顶顶
                                顶顶顶顶顶顶顶顶顶顶顶顶顶顶顶
                      顶顶顶顶  顶顶顶顶顶顶顶顶顶顶顶
                顶顶顶顶顶顶顶  顶顶顶    顶顶顶顶顶
      顶顶顶顶顶顶顶顶顶顶顶顶            顶顶顶顶
  顶顶顶顶顶顶顶顶顶顶顶顶顶顶            顶顶顶顶
  顶顶顶顶顶顶顶顶顶顶顶顶              顶顶顶顶顶顶顶顶顶顶顶
  顶顶顶顶顶顶顶顶顶顶顶顶            顶顶顶顶顶顶顶顶顶顶顶顶顶顶
    顶顶顶顶顶顶顶顶顶顶          顶顶顶顶顶顶      顶顶顶顶顶顶顶
                顶顶顶顶          顶顶顶顶            顶顶顶顶顶
                顶顶顶顶        顶顶顶顶    顶顶      顶顶顶顶顶
                顶顶顶顶        顶顶顶顶    顶顶顶顶  顶顶顶顶顶
                顶顶顶顶        顶顶顶顶    顶顶顶顶  顶顶顶顶顶
                顶顶顶顶        顶顶顶顶    顶顶顶    顶顶顶顶顶
                顶顶顶顶        顶顶顶顶    顶顶顶    顶顶顶顶顶
                顶顶顶顶        顶顶顶顶  顶顶顶顶    顶顶顶顶顶
                顶顶顶顶        顶顶顶顶  顶顶顶顶    顶顶顶顶顶
                顶顶顶顶        顶顶顶顶  顶顶顶顶    顶顶顶顶顶
                顶顶顶顶        顶顶顶顶  顶顶顶顶    顶顶顶顶顶
                顶顶顶顶        顶顶顶    顶顶顶顶    顶顶顶顶顶
    顶顶      顶顶顶顶顶        顶顶顶    顶顶顶      顶顶顶顶顶
    顶顶顶顶顶顶顶顶顶顶          顶顶    顶顶        顶顶顶顶顶
      顶顶顶顶顶顶顶顶顶                顶顶顶        顶顶顶顶
          顶顶顶顶顶顶顶                顶顶顶  顶顶顶顶
            顶顶顶顶顶顶              顶顶顶顶    顶顶顶顶
                  顶顶顶            顶顶顶顶顶      顶顶顶顶顶顶顶
                                顶顶顶顶顶顶          顶顶顶顶顶顶
                              顶顶顶顶顶顶            顶顶顶顶顶顶顶
                            顶顶顶顶顶                  顶顶顶顶顶顶
                          顶顶顶顶顶                      顶顶顶顶
                        顶顶顶                              顶顶顶
```


  $$ \boxed{\color{Gold}\LARGE\text{洛谷相关颜色参考表}} $$  

$$
\def\arraystretch{1.2}
\begin{array}{|c|l|l||c|l|l|} \hline
颜色 & 十六进制 & RGB值 & 颜色 & 十六进制 & RGB值  \\ \hline
\color{#52C41A}\text{AC绿} & \text{52C41A} & \text{(82,196,26)} & \color{#FE4C61}\text{入门红} & \text{FE4C61} & \text{(254,76,97)} \\ \hline
\color{#E74C3C}\text{WA红} & \text{E74C3C} & \text{(231,76,60)} & \color{#F39C11}\text{普及-橙} & \text{F39C11} & \text{(243,156,17)} \\ \hline
\color{#9D3DCF}\text{RE紫} & \text{9D3DCF} & \text{(157,61,207)} & \color{#FFC116}\text{普及黄} & \text{FFC116} & \text{(255,193,22)}\\ \hline
\color{#FADB14}\text{CE黄} & \text{FADB14} & \text{(250,219,20)} & \color{#52C41A}\text{普及+提高 绿} & \text{52C41A} & \text{(82,196,26)} \\ \hline
\color{#052242}\text{TLE黑} & \text{052242} & \text{(5,34,66)} & \color{#3498DB}\text{提高+省选-蓝} & \text{3498DB} & \text{(52,152,219)} \\ \hline
\color{#052242}\text{MLE黑} & \text{052242} & \text{(5,34,66)} & \color{#9D3DCF}\text{省选紫} & \text{9D3DCF} & \text{(157,61,207)}  \\ \hline
\color{#052242}\text{OLE黑} & \text{052242} & \text{(5,34,66)} & \color{#0E1D69}\text{NOI黑} & \text{0E1D69} & \text{(14,39,105)}   \\ \hline
\color{#0E1D69}\text{UKE蓝} & \text{0E1D69} & \text{(14,29,105)} & \color{#BFBFBF}\text{未评定灰} & \text{BFBFBF} & \text{(191,191,191)} \\ \hline \hline 
\color{#8E44AD}\text{紫名} & \text{8E44AD} & \text{(142,68,173)} & \color{#52C41A}\text{排行绿} & \text{52C41A} & \text{(82,196,26)} \\ \hline
\color{#E74C3C}\text{红名} & \text{E74C3C} & \text{(231,76,60)} & \color{#F39C11}\text{排行橙} & \text{F39C11} & \text{(243,156,17)} \\ \hline
\color{#E67E22}\text{橙名} & \text{E67E22} & \text{(230,126,34)} & \color{#FADB14}\text{排行黄} & \text{FADB14} & \text{(250,219,20)} \\ \hline
\color{#5EB95E}\text{绿名} & \text{5EB95E} & \text{(94,185,94)} & \color{#E74C3C}\text{排行红} & \text{E74C3C} & \text{(231,76,60)}\\ \hline
\color{#0E90D2}\text{蓝名} & \text{0E90D2} & \text{(14,144,210)} & \color{#52C41A}\text{通过钩绿} & \text{52C41A} & \text{(82,196,26)} \\ \hline
\color{#BFBFBF}\text{灰名} & \text{BFBFBF} & \text{(191,191,191)} & \color{#E74C3C}\text{不通过叉红} & \text{E74C3C} & \text{(231,76,60)} \\ \hline
\hline 
\color{#E74C3C}\text{吉利红} & \text{E74C3C} & \text{(231,76,60)} & \color{#E74C3C}\text{官方比赛红} & \text{E74C3C} & \text{(231,76,60)} \\ \hline
\color{#5EB95E}\text{中平绿} & \text{5EB95E} & \text{(94,185,94)} & \color{#054310}\text{团队比赛绿} & \text{054310} & \text{(5,67,16)} \\ \hline
\color{#000000}\text{凶兆黑} & \text{000000} & \text{(0,0,0)} & \color{#3498DB}\text{个人比赛蓝} & \text{3498DB} & \text{(52,152,219)} \\ \hline \hline
\color{#8E44AD}\text{ACM制紫} & \text{8E44AD} & \text{(142,68,173)} & \color{#5EB95E}\text{Rated绿} & \text{5EB95E} & \text{(94,185,94)} \\ \hline
\color{#F1C40F}\text{IOI制黄} & \text{F1C40F} & \text{(241,196,15)} & \color{#5EB95E}\text{未开始绿} & \text{5EB95E} & \text{(94,185,94)} \\ \hline
\color{#F1C40F}\text{乐多制黄} & \text{F1C40F} & \text{(241,196,15)} & \color{#E74C3C}\text{已结束红} & \text{E74C3C} & \text{(231,76,60)} \\ \hline
\color{#F39C11}\text{OI制橙} & \text{F39C11} & \text{(243,156,17)} & \color{#4290D8}\text{进行中*} & \text{4290D8} & \text{(66,144,216)} \\ \hline \hline
\color{#EFEFEF}\text{背景灰} & \text{EFEFEF} & \text{(239, 239, 239)} & \color{#7F7F7F}\text{小字灰} & \text{7F7F7F} & \text{(127,127,127)} \\ \hline \hline 
\color{#0E90D2}\text{按钮蓝} & \text{0E90D2} & \text{(14,144,210)} & \color{#3498DB}\text{链接蓝} & \text{3498DB} & \text{(52,152,219)} \\ \hline 
\color{#DD514C}\text{按钮红} & \text{DD514C} & \text{(221,81,76)} & \color{#3498DB}\text{通过率蓝} & \text{3498DB} & \text{(52,152,219)} \\ \hline \hline 
\color{#FFE169}\text{金钩黄} & \text{FFE169} & \text{(255,225,105)} & \color{#F5CECD}\text{背景粉} & \text{F5CECD} & \text{(245,206,205)} \\ \hline
\color{#5EB95E}\text{绿钩绿} & \text{5EB95E} & \text{(94,185,94)} & \color{#C9E7C9}\text{背景绿} & \text{C9E7C9} & \text{(201,231,201)} \\ \hline
\color{#3498DB}\text{蓝钩蓝} & \text{3498DB} & \text{(52,152,219)} & \color{#CAEBFB}\text{背景蓝} & \text{CAEBFB} & \text{(202,235,251)} \\ \hline \hline 
\color{#3498DB}\text{题目来源蓝} & \text{3498DB} & \text{(52,152,219)} &\color{#7F7F7F}\text{灰色} & \text{7F7F7F} & \text{(127,127,127)} \\ \hline
\color{#E74C3C}\text{题目算法红} & \text{E74C3C} & \text{(231,76,60)}& \color{#FFFFFF}\text{白色} & \text{FFFFFF} & \text{(255,255,255)} \\ \hline
\color{#52C41A}\text{题目地点绿} & \text{52C41A} & \text{(82,196,26)}& \color{#000000}\text{黑色} & \text{000000} & \text{(0,0,0)} \\ \hline
\end{array}
$$



# 致谢

本剪切板大部分都为转载，以下是收集名单（洛谷）：

- @ran_qwq
- @_Hikouwastaken_ 
- @YeKaiYuan 
- @LPhang
- @LiJoQiao

可能有重复！！！
