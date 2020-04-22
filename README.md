# Final Papers for Gov 1006 in Spring 2020

This repository contains the final papers for Gov 1006 at Harvard University in the Spring of 2020.

### Do This

* Make sure to pull before you push. Deal with [merge conflicts](https://www.git-tower.com/learn/git/ebook/en/command-line/advanced-topics/merge-conflicts) intelligently. After you edit, push your changes and confirm that they [look good on the web](https://github.com/davidkane9/gov_1006_spring_2020_papers).

* Edit this file. Use the exact same template as Debi did. Enter your name in alphabetical order, skipping one row between each. The pdf link should go to the pdf in this repo, not to the pdf in your own repo.

* Give your pdf a name which starts with your last name. (We can't have multiple files all called "mypaper.pdf.") Place it in the papers/ directory.

### Students

[Miroslav Bergam](https://github.com/mirobergam) --- ([repo](https://github.com/mirobergam/Replication-paper) [pdf](https://github.com/mirobergam/Replication-paper/blob/master/Bergam.pdf)) --- Zelizer (2019) finds that the cues that legislators take from their peers, in addition to other credible sources of information like briefings, influence their policymaking decisions. I succesfully replicated Zelizer’s results. Zelizer took a Bayesian approach to his findings, running 10,000 simulations for each table and figure using for-loops to produce estimates and standard deviations; however, this made his code inefficient and extremely slow Using the rstanarm package, I was able to simplify his code while maintaining the Bayesian integrity of the study. This extension served as both a robustness test of his results and a simplification that makes the study more easily reproducable.

[Maria Burzillo](https://github.com/mburzillo/) ---([repo](https://github.com/mburzillo/new_final_project) [pdf](https://github.com/mburzillo/new_final_project/blob/master/Milestone_7.pdf)) --- Trounstine’s Segregation and Inequality in Public Goods (2016) suggests that residential segregation is associated with both political polarization and decreased public spending. In this analysis, I was able to successfully replicate Trounstine (2016)’s main results. Adding onto her original analysis, I impute a large amount of missing data from the original dataset and re-run the analysis. Finally, I add in income segregation as a predictor in her regressions to assess whether this could be a confounding variable. 

[Evelyn Cai](https://github.com/caievelyn) --- ([repo](https://github.com/caievelyn/milestone/) [pdf](https://github.com/GOV-1006-Spring-2020/papers/blob/master/papers/Cai_voter_preferences.pdf)) --- This is an  extension of the research conducted by Horiuchi, Smith, and Yamamoto (2020), which determined that Japanese voters' voting preferences are dependent on external factors such as party recruitment. Their conclusion was facilitated by the difference between observational data and their conjoint survey results, which yielded consistent voter preferences across different levels of knowledge on electoral systems; I was able to successfuly replicate these results. The extension focuses on examining the difference in marginal means instead of the difference of average marginal component effects, which has been found to be a more appropriate metric that avoids setting a baseline when calculating treatment effects according to Leeper et al. (2018).  

[Molly Chiang](https://github.com/mollyechiang) --- ([repo](https://github.com/mollyechiang/1006_milestone_6) [pdf](https://github.com/mollyechiang/replication/blob/master/chiang_edu_and_voting.pdf)) --- Marshall (2015) shows the causal effect of additional years of schooling on voting conservative in his analysis og voting records before and after the British 1947 school-leaving age reform. Marshall's figures and the results of his tables were replicated in Stata, but an update in the rdrobust package lead to my modification of his bandwidth selection code, and thus slightly different coefficients. In an extension of Marshall's work I investigated how his observed effect differed between genders. Running rdrobust and creating regression discontinuity figures on male and female subsets of the data revealed the effect of more years of education increasing likelihood of voting conservative was much stronger in women than men. This finding could complicate Marshall's argument that more education leads to higher income and then to more conservative political opinions and perhaps reveals something about the differing effect of education on men and women. 

[Ali Crump](https://github.com/alicrump) --- ([repo](https://github.com/alicrump/Fentanyl_Replication_Project) [pdf](https://github.com/alicrump/Fentanyl_Replication_Project/blob/master/milestone7.pdf)) --- Zoorob (2019) shows that geography and fentanyl exposure explain much of the variation in increased overdose mortality rates between 2011 and 2017. This paper succeeds in replicating all of the figures and tables in Zoorob’s research with the exception of Table 2B, the total estimated deaths attributable to fentanyl by each model. The estimates from table in the original publication more closely match official mortality statistics than the ones replicated in this paper. In addition to replicating Zoorob’s work, the extension of this paper aims to improve the two-stage least squares regression analysis by performing a TBD alternative strategy to analyze the instrumental variables. In my analysis I find X, which matters because Y.

[Drake Deuel](https://github.com/ddeuel) --- ([repo](https://github.com/ddeuel/Bikeshare-Replication) [pdf](https://github.com/davidkane9/gov_1006_spring_2020_papers/papers/bikeshare_deuel.pdf)) --- This is an extension and replication of the research done by Fullter et al. (2019) which used the Philadelphia's transit workers strike from November 1-7, 2016, to generate a natural experiment in which other means of transit were interrupted to study the impact on bikeshare ride usage.

[Angela Fu](https://github.com/angelafu7) ---
([repo](https://github.com/angelafu7/CrossingTheLineReplication) [pdf](https://github.com/angelafu7/CrossingTheLineReplication/blob/master/fufinalpaper.pdf)) --- In their paper "Crossing the Line: Local Ethnic Geography and Voting in Ghana," Nahomi Ichino and Noah Nathan found that the local ethnic demographics of the area in which Ghanian voters live affected who they chose to support in the 2008 Ghana presidential election. I have reexamined their models and added an additional variable to explore the effect of a voter's trust in members of their own ethnicity.  

[Michelle Gao](https://github.com/michgao87) --- ([repo](https://github.com/michgao87/replication) [pdf](https://github.com/GOV-1006-Spring-2020/papers/blob/master/papers/gao_tech_politics.pdf)) --- Broockman, Ferenstein, and Malhotra (2019) show that technology entrepreneurs have a unique set of political beliefs: they are liberal on social issues, globalism, and redistribution, but very conservative on government regulation.

[Debora Gonzalez](https://github.com/deboragonzalez) --- ([repo](https://github.com/deboragonzalez/Milestones) [pdf](https://github.com/GOV-1006-Spring-2020/papers/blob/master/papers/GonzalezDebi_Replication.pdf)) --- Hopkins and colleagues (2019) argue that demographic changes at low levels of aggregation are not associated with increased vote shifts toward an anti-immigration presidential candidate between 2012 and 2016. More specifically, the authors' estimates find little evidence that influxes of Hispanics or noncitizen immigrants benefited Trump relative to past Republicans, instead they indicate that such demographic changes were associated with shifts to Clinton. This is a replication and extension project of the "Local demographic changes and US presidential voting, 2012 to 2016" study by Seth J. Hilla, Daniel J. Hopkins, and Gregory A. Huberc, which explored how demographic changes from 2000 to 2016 affected the 2016 general election outcome. The topics of immigration and the increase of racial and ethnic minorities have been fairly prevalent in media, social media, and political rhetoric over the last few years, but do these phenomena actually influence voting behavior? This study analyzes voting patterns in areas that received an influx of immigrants prior to the 2016 general election. This document presents the working replication exercise of the afore-mentioned academic paper through a textual overview of the authors' findings and methods, a high-level visual presentation of the data, and a close-replication of the original analysis. It also contains an extension proposal, which will become the core of this project, as a form of critique, development, and/or expansion of the original findings. Currently, 3 out of the 6 proposed extension analysis have been addressed.

[Carine Hajjar](https://github.com/carine-h)---
([repo](https://github.com/carine-h/replication-project))---
[PDF](https://github.com/carine-h/replication-project/blob/master/final_project_carine_hajjar.pdf)--- Barber and Pope (2018) show that the electorate is more influenced by party position than real ideology. The results of the paper and the replication indicate that party loyalists vote in line with their leader, regarless of the political content of their leader's cues. More specifically, voters with low political knowledge, high partisanship, and high approval of their leader are more likely to support their leader's cues, regardless of the true ideological implications, even if they are not in line with the party's traditional views. I looked at Barber and Pope's regressions testing the causal effect of conservative and liberal cues from President Trump on Republican, Democrats, and Independents with varying levels of political knowledge, partisanship, approval of Trump, and political ideology. I took the regression on partisanship and knowledge as well as the overall regression of average cue response among all political identities and ran a more robust binomial regression as well as corrected for a mistake in the first figure of the paper. I found that party loyalists are not necessarily ideological loyalists and, more specifically, that many Republicans respond positively to liberal or conservative cues from Trump but not necessarily from others. This finding forces Americans to rethink the importance of parties and the ideological strength of their positions. 

[Benjamin Hoffner-Brodsky](https://github.com/ben-hb) --- ([repo](https://github.com/ben-hb/development_without_representation_replication) [pdf](https://github.com/ben-hb/development_without_representation_replication/blob/master/milestone_4.pdf)) --- I'm replicating Jensenius (2015) *Development from Representation*, which appeared in the *American Economic Journal: Applied Economics*. Since 1950, the Indian Parliament and India's state assemblies have guaranteed a minimum number of seats to Scheduled Castes (SCs). Ensuring ascriptive representation for the 16% of Indian citizens who belong to SCs was intended, in part, as a mechanism to equitably allocate resources along caste lines. To implement SC quotas, the federal government non-randomly selected constituencies in which only SC members can run for office, though all members of the constituency are allowed to vote. The paper uses a dataset of constituency-level data of 3,134 state assembly constituencies from the 15 largest Indian states to compare development levels across reserved and non-reserved constituencies in 1971 and 2001. As reserved constituencies were non-randomly determined, Jensenius forms pairs of reserved and non-reserved constituencies, matching based on pre-selection characteristics to mitigate the effect of selection bias. She finds a null constituency-level effect on overall development, redistribution to SCs, literacy rates, SC employment patterns, and village amenities.

[Suriya Kandaswamy](https://github.com/sardination/) --- ([repo](https://github.com/sardination/gov1006-final-project) [pdf](https://github.com/GOV-1006-Spring-2020/papers/blob/master/papers/Kandaswamy_Dynamic_responsiveness.pdf)) --- This is an extension of "Policy Preferences and Policy Change: Dynamic Responsiveness in the American States, 1936-2014" by Caughey and Warshaw (2018) which takes a look at the responsiveness of state policy liberalism to mass liberalism based on public opinion while taking into account legislative party control, geography, and other factors.

[Alexander Klueber](https://github.com/Alex1005-stack) --- ([repo](https://github.com/Alex1005-stack/Website_use) --- [pdf](https://github.com/Alex1005-stack/Website_use/blob/master/Klueber_website_use.pdf)) --- 
Pan (2017) shows that the emphasis on Chinese local government websites on either the competence or benevolence of county executives depends on where they are in the political tenure cycle. I was largely able to replicate these results. My extension confirms that this is the most likely explanation for the observed effect by comparing the statistical explanatory power of alternative models (e.g. cultural differences among regions, gender differences, etc.) through the leave one out method. In addition I validate the geographical randomness of the sample through simulations of repeated sampling and the construction of confidence intervals. They corraborate the findings of the paper by confirming the geographic randomness of the sample.

[Samuel Lowry](https://github.com/SamuelLowry) --- ([repo](https://github.com/SamuelLowry/why_friends_and_neighbors_replication_paper) [pdf](https://github.com/SamuelLowry/why_friends_and_neighbors_replication_paper/blob/master/milestone-7.pdf)) --- Campbell et al. (2019) details two separate experiments which suggest that individuals think of politicians with local roots and that exibit behavioral localism more highly. I was able to replicate the entire article with the exceptions of table 1 and figure 2 because they visuals relating to methodology and not the results themselves. I will be conducting an extension which includes the use of stan_glm instead of lm as well as look at certain subgroups based upon location and party identification. I hope to find cool things:)

[Chelsea Marlborough](https://github.com/chelseamarlborough) --- ([repo](https://github.com/chelseamarlborough/gov1006-finalpaper)) [pdf](https://github.com/chelseamarlborough/gov1006-finalpaper/blob/master/marlborough_final.pdf)) --- Stokes (2015) finds that voters do pay attention to climate policy and afterwards penalize the incumbent governments for facilities viewed as harmful to the communities.

[Diego Martinez](https://github.com/diegomartinez1221) --- ([repo](https://github.com/diegomartinez1221/gov_1006_replication), [pdf](https://github.com/GOV-1006-Spring-2020/papers/blob/master/papers/Martinez_local_roots.pdf)) Campbell et al (2019) show that candidate's with shared local roots appeals to voters and that having local roots is an important factor in a voter's candidate selection. I was successfully able to replicate all the results presented in the orignal article "Why Friends and Neighbors? Explaining the Electoral Appeal of Local Roots." by Rosie Campbell, Philip Cowley, Nick Vivyan, Markus Wagner. To further their analysis, I modeled how local roots influence different sub-populations including males vs. females voters as well as between different age groups. I found the average marginal effect of local roots to not remain constant across subgroups, meaning local roots affect groups of voters differently. Thus, any further research regarding local roots effects should consider the gender as well as age makeup of the sample.  

[Liz Masten](https://github.com/LizMas) ---
([repo](https://github.com/LizMas/1006_replication)
[pdf](https://github.com/LizMas/1006_replication/blob/master/1006_replication.pdf)) ---
Findley, Piazza, and Young (2012) show that interstate rivalries are a positive predictor of transnational terrorist activity. The authors argue that terrorism is often a component of broader hostilities that can be emperically analyzed using a series of politicaly relevant directed dyads. While this paper is a successful replication of their work, I call into question their choice to use dyadic analysis. When using country-year analysis, I find that ... TBD. 

[Beau Meche](https://github.com/BeauMeche) --- 
([repo](https://github.com/BeauMeche/enforcement_distribution_electorate)
[pdf](https://github.com/BeauMeche/enforcement_distribution_electorate/blob/master/Meche_enforcement_variance.pdf)) --- "The Distributive Politics of Enforcement" by Alisha Holland (2014) analyzes electoral behavior's relationship with police action in opposition to low-income unlicensed street vendors in three cities in Latin America. I was mostly successful in replicating the results, with minute variance due to apparent differences between regression output between R and Stata. In my extenstion I re-regressed the models from the original paper under Bayesian modeling methods in the interest of discovering any differences likely to arise. The regression outputs themselves were quite similar and model comparisons favored similar models to the author; however upon cross-validation model analysis I found that a majority of the models were laden with 'problematic' values. This implies that the models showing statistically significant support for the author's claim do not effectively model the original dataset should any one value be removed and further implies that caution should be taken with associated claims pending better modeling or more data. 

[Robert McKenzie](https://github.com/rmckenzie11) --- ([repo](https://github.com/rmckenzie11/Replication_1006) [pdf](https://github.com/GOV-1006-Spring-2020/papers/blob/master/papers/McKenzie_Geography_Represenatation.pdf)) --- "The Achilles Heel of Multiparty Democracies", by Ernesto Calvo and Jonathan Rodden (2014) shows that majoritarianbiases increase with the number of parties, and majoritarian systems harm small parties when their vote is more dispersed than average, and large parties when their vote is more concentrated than average. They built a mathematical model of the relationship between geographic distribution and electoral representation, using MC methods, and then analyzed UK elections over the past 60 years to determine which parties benefit from majoritarian bias. I've extended their paper by filtering the UK election data so that it better fits the assumptions of their model.

[Alexandra Norris](https://github.com/asnorris) --- ([repo](https://github.com/asnorris/Replication_1006) --- [original paper](https://journals.sagepub.com/doi/abs/10.1177/0010414017730079) and [data verse](https://journals.sagepub.com/doi/suppl/10.1177/0010414017730079) --- This paper is a replication of the work conducted by Ejdemyr et al. (2017): "Segregation, Ethnic Favoritism, and the Strategic Targeting of Local Public Goods".

[Cris Patvakanian](https://github.com/cpatvakanian) --- ([repo](https://github.com/cpatvakanian/milestone_6.5) [pdf](https://github.com/cpatvakanian/milestone_6.5/blob/master/milestone_6.5.pdf)) --- I am replicating “Vote Brokers, Clientelist Appeals, and Voter Turnout: Evidence from Russia and Venezuela” by Timothy Frye, Ora John Reuter and David Szakonyi. They analyze voting patterns and clientelism in Russia and Venezuela through the use of original survey data. They also run fixed effect linear regressions to see what influence the skewing of the voting turnout for a couple of different types of leverage, looking specific demographics of the type of individuals which are classified as brokers. This paper ultimately finds that in Russia and Venezuela, different types of brokers and methods can influence voter turnout differently, which seems to be expected. All analysis for this paper be found in the [original paper](https://www.cambridge.org/core/journals/world-politics/article/vote-brokers-clientelist-appeals-andvoter-turnout-evidence-from-russia-and-venezuela/45FE0BE1216FCD8744B02A82919B328A) and [data verse](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/YSVMS2).

[Pieter Quinton](https://github.com/PGQuinton) ---  ([repo](https://github.com/PGQuinton/gov1006-finalproject-2.0), [pdf](https://github.com/GOV-1006-Spring-2020/papers/blob/master/papers/quinton_unemployment.pdf)) --- "Bauer (2018) finds that there is no consistent relationship between unemployment and one's trust in government and their satisfaction with democracy. I was able to completely replicate the majority of his findings aside from a summary table of the data. My extension evaluates how consistent or long-term unemployment may impact one's views. Rather than examining the effects of just a single year of unemployment, as Bauer did, I track unemployement trends over longer periods of time to see if extended periods of unemployment have a stronger impact on one's feelings towards the government and its institutions."

[Timothy Ravis](https://github.com/soetimno) --- ([repo](https://github.com/soetimno/ravis_1006_final_project.git) [pdf](https://github.com/GOV-1006-Spring-2020/papers/blob/master/papers/Tim_Ravis_Deforestation_and_Titling.pdf)) --- Buntaine, et al (2015) find that donor-financed, government-implemented land tenure legalization efforts in forested areas have a negligible effect on the rate of deforestation versus that found in areas not subject to such an intervention. After matching treated plots with untreated ones, they find no significant treatment affect on deforestation rates. The major results of their analysis were successfully replicated in this study. In the present paper, I explore how spatial autocorrelation in both the treatment and the outcome affects the treatment effect found by the original authors. This illustrates the importance of including spatial relationships into models attempting to explain causality within explicitly spatial datasets.

[Daniel Shapiro](https://github.com/dfshapir) --- ([repo](https://github.com/dfshapir/Replication) [pdf](https://github.com/dfshapir/Replication/blob/master/Shapiro_Chechnya.pdf)) --- Lazarev (2019) uses data describing individuals’ choice between Russian state law, sharia law and customary law (adat) in Chechnya to show that gender can play a large role in societal splits in post-conﬂict societies. I was able to replicate all of the author’s results. In my extension to Lazarev’s paper, used the rstanarm package in R to check Lazarev’s analysis with Bayesian regression, and the results conﬁrmed the author’s ﬁndings. I also pointed out certain areas where I disagreed somewhat with Lazarev’s analysis and where I felt that the paper could improve. This paper’s successful replication of Lazarev’s ﬁndings helps strengthen Lazarev’s argument about the role of gender in choice of legal organ, and my additional comments on Lazarev’s anaylsis help to further discussion about postwar Chechnya and post-conﬂict society as a whole.

[Mike Silva ](https://github.com/mikesilva23) --- ([repo](https://github.com/mikesilva23/replication_1006) [pdf](https://github.com/GOV-1006-Spring-2020/papers/blob/master/papers/SilvaPaper.pdf)) --- Tingley et al (2014) find that olfactory senses could explain assortative mating by ideology. My replication of this paper succeeded in most cases. It failed in a few ways including clustering standard errors around certain variables and recreating graphs that used 21 specific observations from the data set. Through my extension, I evaluate one of the three models Tingley et al uses by using a bayesian fit instead of a regular linear model. I further create a posterior distribution of predictions on the outcome variable using the model and graph those predictions with the actual outcome values. Through this model, I confirm that Tingley's model significantly explains the data.  

[Cian Stryker](https://github.com/CianStryker) --- ([repo](https://github.com/CianStryker/Prosocial_Behavior) [pdf](https://github.com/GOV-1006-Spring-2020/papers/blob/master/papers/Stryker_Prosocial_Behavior.pdf)) --- Hager, Krakowsi, and Schaub (2019) find that exposure to ethnic violence negatively affects prosocial behavior within and across ethnic groups in Osh, Kyrgyzstan. I was largely successful in replicating their main results and use their survey data of Kyrgyz and Uzbeks—the majority and minority ethnic groups of Osh—to expand upon their work. I find that the prosocial behavior of Kyrgyz towards Uzbeks is partially positively affected by exposure to violence. These results contradict the authors’ original findings that exposure to ethnic violence has a homogenous treatment effect. My models demonstrate that on the contrary, ethnic violence can have a heterogenous treatment effect, which warrants further analysis of ethnic violence’s influence on interethnic relations.

[Amanda Su](https://github.com/amanda-y-su) --- ([repo](https://github.com/amanda-y-su/race-writing-computation) [pdf](https://github.com/GOV-1006-Spring-2020/papers/blob/master/papers/su_race_computation.pdf)) --- So, Long, and Zhu (2019) determine that black writers who cite the Bible are more likely to cite it in a social context compared to white writers who cite the Bible in their novels. I was able to successfully replicate the results of the authors' paper. For my extension, I decided to reconstruct the paper's primary model using a Bayesian approach. I found that the results of the model were largely the same the as that of the original. These robust results corroborate the author's conclusions about how race and writing intersect across more than a century of US fiction.

[Abrar Trabulsi](https://github.com/abrartrabulsi) --- ([repo](https://github.com/abrartrabulsi/finalproject1006) [pdf](https://github.com/GOV-1006-Spring-2020/papers/blob/master/papers/Trabulsi_Abrar_workingdraft.pdf)) --- In his paper 'The Desire for Social Status and Economic Conservatism among Affluent Americans', Thal (2020) shows that affluent American's desire for social status drives conservative attitudes amongst them, and the will to advance economically conservative politics. Overall, I was successful in my replication efforts in this paper. 

[Hannah Valencia](https://github.com/h-valencia) --- ([repo](https://github.com/h-valencia/Firearms-Replication) [pdf](https://github.com/h-valencia/Firearms-Replication/blob/master/FirearmsRepPaper.pdf)) --- Levine and McKnight (2017) show that in the 5-month period following the Sandy Hook school shooting in December 2012, a large spike in gun sales contributed to an increase in accidental firearm deaths. Their findings conclude that there was a spike in accidental firearm deaths resulting from the increase in exposure, which is confirmed in this replication. As an extension to this paper, the "post-Sandy Hook window" has been redefined from the 5-month period following the shooting to the 4-month period following. After changing this time period and running the regression again, the results found still hold, showing an increase in gun deaths following Sandy Hook. Even though the Sandy Hook shooting showed the need for stricter gun laws, the immediate aftermath of this realization led to the opposite effect as desired: more accidental firearm deaths.

[Kevin Wang](https://github.com/kevpwang) --- ([repo](https://github.com/kevpwang/replication_project) [pdf](https://github.com/GOV-1006-Spring-2020/papers/blob/master/papers/wang_draft.pdf)) --- Hopkins (2015) finds that exposing survey respondents to video of an immigrant with "culturally distinctive" traits causes the respondents to adopt more inclusive attitudes toward immigration. I successfully replicated Hopkins's results and extended his model to account for varying levels of preexisting Spanish exposure among respondents that might influence their responses to such traits.


[Yao Yu](https://github.com/itsyaoyu) --- ([repo](https://github.com/itsyaoyu/mass-shooting-intervals) [pdf](https://github.com/davidkane9/gov_1006_spring_2020_papers/papers/yu_mass_shooting_intervals.pdf)) --- Lin et al. (2018) found that the time interval between mass shootings has been drastic decreasing in the past three decades, suggesting that the rate of shootings are increasing. I managed to replicate most of the graphics from Lin et al. (2018) with the exception of table 1, where I was unable to recreate the exact zero-inflated poisson model. My extension broke down the interval trends between different venues of shootings showing in figure 2 of Lin et al. (2018). What I found was that the interval trend of mass school shootings remained relatively steady while the interval of mass workplace shootings drastically decreased and the overall interval also decreased. This finding suggests that the 2008 financial crisis might have played a major role in the decreasing interval of mass shootings.

[Ruth Zheng](https://github.com/zhengruth) --- ([repo](https://github.com/zhengruth/milestone) [pdf](https://github.com/zhengruth/milestone/blob/master/When%20Renters%20Behave%20Like%20Homeowners.pdf)) --- Hankinson (2018) shows that renters exhibit "Not in My Back Yard" (NIMBY) behavior on par with homeowners in high-rent cities despite overall support for a housing supply increase. This increased likelihood to oppose policies that create new housing helps explain the affordable housing crisis in major American cities. 
