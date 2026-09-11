# 定义一个复数类complex重载运算符+使之能（定义一个复数类complex重载运算符）

> 更新时间：2026-09-10 (UTC+8)

您好,今天小编胡舒来为大家解答以上的问题。定义一个复数类complex重载运算符+使之能，定义一个复数类complex重载运算符相信很多小伙伴还不知道,现在让我们一起来看看吧！

1、#include using namespace std;class CComplex{ private: float real, image; public: CComplex() { } CComplex( float r, float img ) { real = r; image = img; } CComplex( CComplex another ) { real = another.real; image = another.image; } CComplex operator = (CComplex another ) { real = another.real; image = another.image; return this; } CComplex operator +( CComplexanother ) { return CComplex( real+ another.real, image + another.image ); }CComplex operator -( CComplexanother ) { return CComplex( real- another.real, image - another.image ); }CComplex operator ( CComplexanother ) { CComplex prod; //prod = this;prod.real = realanother.real - imageanother.image; prod.image = realanother.image + imageanother.real; return prod; //return CComplex( real+ another.real, image + another.image ); } CComplex operator /( CComplexanother ) { CComplex quot; float sq = another.realanother.real + another.imageanother.image; quot.real = (realanother.real + imageanother.image)/sq; quot.image = (imageanother.real - realanother.image)/sq; return quot; }};void main(){ CComplex c1( 2, 3 ), c2( 3, 3 ); CComplex c4, c5, c6, c7; c4 = c1 + c2; c5 = c1 - c2; c6 = c1c2; c7 = c1/c2;}。

本文就为大家分享到这里，希望小伙伴们会喜欢。

## 相关阅读

- [深圳三代试管助孕需要多少钱？](https://github.com/zntce2ojnh/child-care-essays/blob/main/20260910juci/amvyptqdfl.md)
- [孩子是否已经暗示了喜欢你？不要因为不懂而错过。](https://github.com/y9qvvxks1i/parenting-daily-tips/blob/main/20260910jwcv/rcgotoyucd.md)
- [广西壮族自治区生殖医院做试管可以选.婴.女吗?](https://github.com/y9qvvxks1i/mommy-baby-notes/blob/main/20260910mfuo/sramkucumg.md)
- [深圳试管婴儿可以走医保吗？](https://github.com/y9qvvxks1i/child-care-essays/blob/main/20260910cskn/vvcuruasnw.md)
- [泰国试管婴儿要多少钱性价比怎么样](https://github.com/zntce2ojnh/pregnancy-care-hub/blob/main/20260910xuzh/vuvdmvhful.md)
- [柬埔寨第三代试管婴儿费用高吗，大概要多少钱](https://github.com/n9ugyolxwj/child-care-essays/blob/main/20260910ipuc/gqmljmxrgg.md)
- [深圳试管生男宝医院推荐，这15家机构都是明智选择！](https://github.com/p35ieeld8a/parenting-daily-tips/blob/main/20260910yjru/jqheyiqxnc.md)
- [国内三代试管包生男孩价格，附国内外试管费用一览！](https://github.com/h5z4rt20ta/pregnancy-care-hub/blob/main/20260910xyeh/kjwhsawzkf.md)
- [美国试管一般多少钱呢？花费明细是多少钱？](https://github.com/syevx32qjy/parenting-daily-tips/blob/main/20260910hkym/bgailfjbjb.md)
- [国内哪里可以借卵生子?沈阳二〇四医院做试管可以用别人卵泡吗](https://github.com/n9ugyolxwj/mommy-baby-notes/blob/main/20260910lrxg/sejldehhsj.md)
- [三代试管中胚胎养成囊胚概率探讨：从十个胚胎到两个囊胚，发育过程是否普遍正常？](https://github.com/ij0s3j0vss/baby-care-journal/blob/main/20260910lfli/bpnpyzfouy.md)
- [做试管婴儿需要多久，做试管的价格！](https://github.com/gamvlx2qer/family-health-notes/blob/main/20260910fcoq/cimbvixzwy.md)

## 推荐站点

- [['https://www.xmxinyhwzhs.cn/29320649943494.html', '卵巢早衰代生包儿子成功率高吗']](https://www.xmxinyhwzhs.cn/29320649943494.html)
- [['https://www.eduency.com/138085099146.html', '深圳无卵供卵助孕医院,深圳仁合医院可以试管吗！深圳仁合医院是私立医院吗！']](https://www.eduency.com/138085099146.html)
- [['https://www.3899234.com/20250927-5.html', '代怀孕花费&东莞第三代试管贵不贵']](https://www.3899234.com/20250927-5.html)
- [['https://www.mimi567.com/82.html', '正规试管代怀:2次稽留流产可以做试管-稽留流产两次去做什么检查']](https://www.mimi567.com/82.html)
- [['https://www.dygsdyw.com/221612996494.html', '供卵包怀男孩:子宫后壁是什么意思？子宫底后壁顺产容易吗？']](https://www.dygsdyw.com/221612996494.html)
- [['https://www.dyokx.com/shiguandaihuaijiage/82.html', '代孕成功几率-金华试管婴儿总共要花多少钱？金华试管婴儿费用？']](https://www.dyokx.com/shiguandaihuaijiage/82.html)
- [['https://www.sasksjob.com/427602819139.html', '详解试管婴儿降调药物：助孕关键的用药指南']](https://www.sasksjob.com/427602819139.html)
- [['https://www.cd-hssf.com/307661995303.html', '山东附属生殖医院能做借卵试管婴儿吗？需要多长时间？']](https://www.cd-hssf.com/307661995303.html)
- [['https://www.hs52.cc/sandaigongluandaihuai/75.html', '着床不稳的征兆']](https://www.hs52.cc/sandaigongluandaihuai/75.html)
- [['https://www.ewdboe.cn/227473678110.html', '贵州靠谱的私立供卵试管医院名单更新，2026供卵生男孩费用明细公开 ,代孕机构排名']](https://www.ewdboe.cn/227473678110.html)
- [['https://www.cecigou.cn/chuanchengguojidaiyun/20250928/14919.html', '试管反复失败怎么检查出来？试管婴儿反复失败']](https://www.cecigou.cn/chuanchengguojidaiyun/20250928/14919.html)
- [['https://www.bjwdzxkj.cn/3557090855556.html', '西藏代生双胞胎包儿子成功率高的医院排名榜揭晓']](https://www.bjwdzxkj.cn/3557090855556.html)
- [['https://www.sdxxy.cn/20250530-482.html', '代孕供卵机构,女性不孕导致试管婴儿的原因是什么！不孕不育试管婴儿会遗传']](https://www.sdxxy.cn/20250530-482.html)

*本文整理自母婴健康资讯，仅供科普参考。*
