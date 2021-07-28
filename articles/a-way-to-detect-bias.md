# A Way to Detect Bias

**Kaynak:** [http://paulgraham.com/bias.html](http://paulgraham.com/bias.html)

**Yazar:** Paul Graham

**Çeviren:** Bora KIŞ

## Türkçe
Ekim 2015 
 
Bu, birçok insana şaşırtıcı gelecektir, ancak bazı durumlarda, aday havuzu hakkında hiçbir şey bilmeden bir seçim sürecindeki önyargıyı tespit etmek mümkündür. Bu ilginç, çünkü diğer şeylerin yanı sıra, üçüncü tarafların bu tekniği, seçimi yapanların isteyip istemediklerini tespit etmek için kullanabilecekleri anlamına geliyor. 

Bu tekniği, (a) seçilen adaylardan en azından rastgele bir örneğiniz olduğunda, (b) sonraki performansları ölçüldüğünde ve (c) karşılaştırdığınız aday grupları kabaca eşit dağılıma sahip olduğunda kullanabilirsiniz. 

Nasıl oluyor peki? Önyargılı olmanın ne demek olduğunu bir düşünün. Bir seçim sürecinin x tipi adaylara karşı önyargılı olmasının anlamı, onların bunu başarmalarının daha zor olmasıdır. Bu, x tipi adayların seçilmek için x tipi olmayan adaylardan daha iyi olması gerektiği anlamına gelir. [1] Bu, seçim sürecinden geçen x tipi adayların diğer başarılı adaylardan daha iyi performans göstereceği anlamına gelir. Ve tüm başarılı başvuru sahiplerinin performansı ölçülürse, bunu yapıp yapmadıklarını anlayacaksınız. 

Elbette, performansı ölçmek için kullandığınız testin geçerli bir test olması gerekir. Ve özellikle, ölçmeye çalıştığınız önyargı tarafından geçersiz kılınmamalıdır. Ancak performansın ölçülebildiği bazı alanlar vardır ve bu alanlarda önyargıyı tespit etmek basittir. Seçim sürecinin bir tür başvuru sahibine karşı önyargılı olup olmadığını bilmek ister misiniz? Diğerlerinden daha iyi performans gösterip göstermediklerini kontrol edin. Bu sadece önyargıyı tespit etmek için bir buluşsal yöntem değildir. Önyargı bu demektir. 

Örneğin, birçok kişi risk sermayesi şirketlerinin kadın kuruculara karşı önyargılı olduğundan şüpheleniyor. Bunu tespit etmek kolay olurdu: Portföy şirketleri arasında, kadın kurucuları olan girişimler, olmayanlardan daha iyi performans gösteriyor mu? Birkaç ay önce, bir VC firması (neredeyse kesinlikle istemeden) bu tür bir önyargı gösteren bir çalışma yayınladı. First Round Capital, portföy şirketleri arasında, kadın kurucuları olan girişimlerin,  olmayanlardan %63 [daha iyi performans gösterdiğini](http://10years.firstround.com/#one) tespit etti. [2]  
 
Bu tekniğin birçok kişiye şaşırtıcı geleceğini söyleyerek başlamamın nedeni, bu tür analizleri çok nadiren görmemiz. Uyguladıklarında First Round’a şaşırtıcı geleceğinden eminim. Burada örneklemlerini kendi portföyleriyle sınırlayarak şirket seçerken startup trendlerine değil, kendi önyargılarına yönelik bir çalışma ürettiklerinin farkında olan biri olduğunu sanmıyorum.

Bu tekniğin gelecekte daha çok kullanıldığını göreceğimizi tahmin ediyorum. Bu tür çalışmaları yürütmek için gereken bilgiler giderek daha fazla erişilebilir durumda. Bir şeyler için kimin başvurduğuna ilişkin veriler, genellikle onları seçen kuruluşlar tarafından yakından korunur; ancak günümüzde kimin seçildiğine ilişkin veriler, genellikle, bunları bir araya getirme zahmetine giren herkes için kamuya açıktır. 

**Notlar**  
 
[1] Seçim süreci farklı başvuru sahiplerinden farklı şeyler ararsa (örneğin, bir işveren erkekleri yeteneklerine göre, kadınları ise dış görünüşlerine göre işe aldıysa) bu teknik işe yaramaz.
[2] Paul Buchheit'in belirttiği gibi, First Round, en başarılı yatırımları olan Uber'i araştırmadan çıkardı. Ve bazı araştırma türlerinden aykırı değerleri hariç tutmak mantıklı olsa da, tamamen aykırı değerleri hedeflemekle ilgili olan startup yatırımlarından elde edilen getiri çalışmaları bunlardan biri değil. 

Bunun taslaklarını okudukları için Sam Altman, Jessica Livingston ve Geoff Ralston'a **teşekkürler**.

## Orijinal
October 2015

This will come as a surprise to a lot of people, but in some cases it's possible to detect bias in a selection process without knowing anything about the applicant pool. Which is exciting because among other things it means third parties can use this technique to detect bias whether those doing the selecting want them to or not.

You can use this technique whenever (a) you have at least a random sample of the applicants that were selected, (b) their subsequent performance is measured, and (c) the groups of applicants you're comparing have roughly equal distribution of ability.

How does it work? Think about what it means to be biased. What it means for a selection process to be biased against applicants of type x is that it's harder for them to make it through. Which means applicants of type x have to be better to get selected than applicants not of type x. [1] Which means applicants of type x who do make it through the selection process will outperform other successful applicants. And if the performance of all the successful applicants is measured, you'll know if they do.

Of course, the test you use to measure performance must be a valid one. And in particular it must not be invalidated by the bias you're trying to measure. But there are some domains where performance can be measured, and in those detecting bias is straightforward. Want to know if the selection process was biased against some type of applicant? Check whether they outperform the others. This is not just a heuristic for detecting bias. It's what bias means.

For example, many suspect that venture capital firms are biased against female founders. This would be easy to detect: among their portfolio companies, do startups with female founders outperform those without? A couple months ago, one VC firm (almost certainly unintentionally) published a study showing bias of this type. First Round Capital found that among its portfolio companies, startups with female founders [outperformed](http://10years.firstround.com/#one) those without by 63%. [2]

The reason I began by saying that this technique would come as a surprise to many people is that we so rarely see analyses of this type. I'm sure it will come as a surprise to First Round that they performed one. I doubt anyone there realized that by limiting their sample to their own portfolio, they were producing a study not of startup trends but of their own biases when selecting companies.

I predict we'll see this technique used more in the future. The information needed to conduct such studies is increasingly available. Data about who applies for things is usually closely guarded by the organizations selecting them, but nowadays data about who gets selected is often publicly available to anyone who takes the trouble to aggregate it.

**Notes**

[1] This technique wouldn't work if the selection process looked for different things from different types of applicants—for example, if an employer hired men based on their ability but women based on their appearance.

[2] As Paul Buchheit points out, First Round excluded their most successful investment, Uber, from the study. And while it makes sense to exclude outliers from some types of studies, studies of returns from startup investing, which is all about hitting outliers, are not one of them.

**Thanks** to Sam Altman, Jessica Livingston, and Geoff Ralston for reading drafts of this.