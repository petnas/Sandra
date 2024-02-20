library(rstatix)
library(devtools)

xtab <- table(duomenys_trumpas$Education, duomenys_trumpas$Continuation)

chisq.test(x=xtab, simulate.p.value = TRUE)

c2$p.value

pairwise_fisher_test(xtab, p.adjust.method = 'bonferroni')


chisq.posthoc.test::chisq.posthoc.test(x=xtab, method = 'bonferroni')

xtab <- table(duomenys_trumpas$Education, duomenys_trumpas$Continuation)

pairwise_fisher_test(xtab, p.adjust.method = 'bonferroni')


chisq.posthoc.test::chisq.posthoc.test(x=xtab, method = 'bonferroni')
