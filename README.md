# Homework-Lab-3
> dat_NYC <- subset(acs2017_ny, (acs2017_ny$in_NYC == 1)&(acs2017_ny$AGE > 20) & (acs2017_ny$AGE < 66))
> attach(dat_NYC)
The following objects are masked _by_ .GlobalEnv:

    female, OWNCOST, PUMA

The following objects are masked from dat_NYC (pos = 3):

    AfAm, AGE, Amindian, ANCESTR1, ANCESTR1D, ANCESTR2, ANCESTR2D, Asian, below_150poverty, below_200poverty, below_povertyline, BPL,
    BPLD, BUILTYR2, CITIZEN, CLASSWKR, CLASSWKRD, Commute_bus, Commute_car, Commute_other, Commute_rail, Commute_subway, COSTELEC,
    COSTFUEL, COSTGAS, COSTWATR, Covid_risk, DEGFIELD, DEGFIELD2, DEGFIELD2D, DEGFIELDD, DEPARTS, EDUC, educ_advdeg, educ_college,
    educ_hs, educ_nohs, educ_somecoll, EDUCD, EMPSTAT, EMPSTATD, FAMSIZE, female, foodstamps, FOODSTMP, FTOTINC, FUELHEAT, GQ,
    has_AnyHealthIns, has_PvtHealthIns, HCOVANY, HCOVPRIV, HHINCOME, Hisp_Cuban, Hisp_DomR, Hisp_Mex, Hisp_PR, HISPAN, HISPAND, Hispanic,
    in_Bronx, in_Brooklyn, in_Manhattan, in_Nassau, in_NYC, in_Queens, in_StatenI, in_Westchester, INCTOT, INCWAGE, IND, IND_number,
    LABFORCE, LINGISOL, MARST, MIGCOUNTY1, MIGPLAC1, MIGPUMA1, MIGRATE1, MIGRATE1D, MORTGAGE, NCHILD, NCHLT5, OCC, OWNCOST, OWNERSHP,
    OWNERSHPD, POVERTY, PUMA, PWPUMA00, RACE, race_oth, RACED, RELATE, RELATED, RENT, ROOMS, SCHOOL, SEX, SSMC, TRANTIME, TRANWORK,
    UHRSWORK, UNITSSTR, unmarried, veteran, VETSTAT, VETSTATD, white, WKSWORK2, YRSUSA1

The following objects are masked from dat_NYC (pos = 5):

    AfAm, AGE, Amindian, ANCESTR1, ANCESTR1D, ANCESTR2, ANCESTR2D, Asian, below_150poverty, below_200poverty, below_povertyline, BPL,
    BPLD, BUILTYR2, CITIZEN, CLASSWKR, CLASSWKRD, Commute_bus, Commute_car, Commute_other, Commute_rail, Commute_subway, COSTELEC,
    COSTFUEL, COSTGAS, COSTWATR, Covid_risk, DEGFIELD, DEGFIELD2, DEGFIELD2D, DEGFIELDD, DEPARTS, EDUC, educ_advdeg, educ_college,
    educ_hs, educ_nohs, educ_somecoll, EDUCD, EMPSTAT, EMPSTATD, FAMSIZE, female, foodstamps, FOODSTMP, FTOTINC, FUELHEAT, GQ,
    has_AnyHealthIns, has_PvtHealthIns, HCOVANY, HCOVPRIV, HHINCOME, Hisp_Cuban, Hisp_DomR, Hisp_Mex, Hisp_PR, HISPAN, HISPAND, Hispanic,
    in_Bronx, in_Brooklyn, in_Manhattan, in_Nassau, in_NYC, in_Queens, in_StatenI, in_Westchester, INCTOT, INCWAGE, IND, IND_number,
    LABFORCE, LINGISOL, MARST, MIGCOUNTY1, MIGPLAC1, MIGPUMA1, MIGRATE1, MIGRATE1D, MORTGAGE, NCHILD, NCHLT5, OCC, OWNCOST, OWNERSHP,
    OWNERSHPD, POVERTY, PUMA, PWPUMA00, RACE, race_oth, RACED, RELATE, RELATED, RENT, ROOMS, SCHOOL, SEX, SSMC, TRANTIME, TRANWORK,
    UHRSWORK, UNITSSTR, unmarried, veteran, VETSTAT, VETSTATD, white, WKSWORK2, YRSUSA1

The following objects are masked from dat_use (pos = 6):

    AfAm, AGE, Amindian, ANCESTR1, ANCESTR1D, ANCESTR2, ANCESTR2D, Asian, below_150poverty, below_200poverty, below_povertyline, BPL,
    BPLD, BUILTYR2, CITIZEN, CLASSWKR, CLASSWKRD, Commute_bus, Commute_car, Commute_other, Commute_rail, Commute_subway, COSTELEC,
    COSTFUEL, COSTGAS, COSTWATR, Covid_risk, DEGFIELD, DEGFIELD2, DEGFIELD2D, DEGFIELDD, DEPARTS, EDUC, educ_advdeg, educ_college,
    educ_hs, educ_nohs, educ_somecoll, EDUCD, EMPSTAT, EMPSTATD, FAMSIZE, female, foodstamps, FOODSTMP, FTOTINC, FUELHEAT, GQ,
    has_AnyHealthIns, has_PvtHealthIns, HCOVANY, HCOVPRIV, HHINCOME, Hisp_Cuban, Hisp_DomR, Hisp_Mex, Hisp_PR, HISPAN, HISPAND, Hispanic,
    in_Bronx, in_Brooklyn, in_Manhattan, in_Nassau, in_NYC, in_Queens, in_StatenI, in_Westchester, INCTOT, INCWAGE, IND, IND_number,
    LABFORCE, LINGISOL, MARST, MIGCOUNTY1, MIGPLAC1, MIGPUMA1, MIGRATE1, MIGRATE1D, MORTGAGE, NCHILD, NCHLT5, OCC, OWNCOST, OWNERSHP,
    OWNERSHPD, POVERTY, PUMA, PWPUMA00, RACE, race_oth, RACED, RELATE, RELATED, RENT, ROOMS, SCHOOL, SEX, SSMC, TRANTIME, TRANWORK,
    UHRSWORK, UNITSSTR, unmarried, veteran, VETSTAT, VETSTATD, white, WKSWORK2, YRSUSA1

The following object is masked from package:survival:

    veteran

The following objects are masked from dat_NYC (pos = 16):

    AfAm, AGE, Amindian, ANCESTR1, ANCESTR1D, ANCESTR2, ANCESTR2D, Asian, below_150poverty, below_200poverty, below_povertyline, BPL,
    BPLD, BUILTYR2, CITIZEN, CLASSWKR, CLASSWKRD, Commute_bus, Commute_car, Commute_other, Commute_rail, Commute_subway, COSTELEC,
    COSTFUEL, COSTGAS, COSTWATR, Covid_risk, DEGFIELD, DEGFIELD2, DEGFIELD2D, DEGFIELDD, DEPARTS, EDUC, educ_advdeg, educ_college,
    educ_hs, educ_nohs, educ_somecoll, EDUCD, EMPSTAT, EMPSTATD, FAMSIZE, female, foodstamps, FOODSTMP, FTOTINC, FUELHEAT, GQ,
    has_AnyHealthIns, has_PvtHealthIns, HCOVANY, HCOVPRIV, HHINCOME, Hisp_Cuban, Hisp_DomR, Hisp_Mex, Hisp_PR, HISPAN, HISPAND, Hispanic,
    in_Bronx, in_Brooklyn, in_Manhattan, in_Nassau, in_NYC, in_Queens, in_StatenI, in_Westchester, INCTOT, INCWAGE, IND, IND_number,
    LABFORCE, LINGISOL, MARST, MIGCOUNTY1, MIGPLAC1, MIGPUMA1, MIGRATE1, MIGRATE1D, MORTGAGE, NCHILD, NCHLT5, OCC, OWNCOST, OWNERSHP,
    OWNERSHPD, POVERTY, PUMA, PWPUMA00, RACE, race_oth, RACED, RELATE, RELATED, RENT, ROOMS, SCHOOL, SEX, SSMC, TRANTIME, TRANWORK,
    UHRSWORK, UNITSSTR, unmarried, veteran, VETSTAT, VETSTATD, white, WKSWORK2, YRSUSA1

The following objects are masked from dat_use1 (pos = 17):

    AfAm, AGE, Amindian, ANCESTR1, ANCESTR1D, ANCESTR2, ANCESTR2D, Asian, below_150poverty, below_200poverty, below_povertyline, BPL,
    BPLD, BUILTYR2, CITIZEN, CLASSWKR, CLASSWKRD, Commute_bus, Commute_car, Commute_other, Commute_rail, Commute_subway, COSTELEC,
    COSTFUEL, COSTGAS, COSTWATR, Covid_risk, DEGFIELD, DEGFIELD2, DEGFIELD2D, DEGFIELDD, DEPARTS, EDUC, educ_advdeg, educ_college,
    educ_hs, educ_nohs, educ_somecoll, EDUCD, EMPSTAT, EMPSTATD, FAMSIZE, female, foodstamps, FOODSTMP, FTOTINC, FUELHEAT, GQ,
    has_AnyHealthIns, has_PvtHealthIns, HCOVANY, HCOVPRIV, HHINCOME, Hisp_Cuban, Hisp_DomR, Hisp_Mex, Hisp_PR, HISPAN, HISPAND, Hispanic,
    in_Bronx, in_Brooklyn, in_Manhattan, in_Nassau, in_NYC, in_Queens, in_StatenI, in_Westchester, INCTOT, INCWAGE, IND, IND_number,
    LABFORCE, LINGISOL, MARST, MIGCOUNTY1, MIGPLAC1, MIGPUMA1, MIGRATE1, MIGRATE1D, MORTGAGE, NCHILD, NCHLT5, OCC, OWNCOST, OWNERSHP,
    OWNERSHPD, POVERTY, PUMA, PWPUMA00, RACE, race_oth, RACED, RELATE, RELATED, RENT, ROOMS, SCHOOL, SEX, SSMC, TRANTIME, TRANWORK,
    UHRSWORK, UNITSSTR, unmarried, veteran, VETSTAT, VETSTATD, white, WKSWORK2, YRSUSA1

The following objects are masked from dat_use1 (pos = 18):

    AfAm, AGE, Amindian, ANCESTR1, ANCESTR1D, ANCESTR2, ANCESTR2D, Asian, below_150poverty, below_200poverty, below_povertyline, BPL,
    BPLD, BUILTYR2, CITIZEN, CLASSWKR, CLASSWKRD, Commute_bus, Commute_car, Commute_other, Commute_rail, Commute_subway, COSTELEC,
    COSTFUEL, COSTGAS, COSTWATR, Covid_risk, DEGFIELD, DEGFIELD2, DEGFIELD2D, DEGFIELDD, DEPARTS, EDUC, educ_advdeg, educ_college,
    educ_hs, educ_nohs, educ_somecoll, EDUCD, EMPSTAT, EMPSTATD, FAMSIZE, female, foodstamps, FOODSTMP, FTOTINC, FUELHEAT, GQ,
    has_AnyHealthIns, has_PvtHealthIns, HCOVANY, HCOVPRIV, HHINCOME, Hisp_Cuban, Hisp_DomR, Hisp_Mex, Hisp_PR, HISPAN, HISPAND, Hispanic,
    in_Bronx, in_Brooklyn, in_Manhattan, in_Nassau, in_NYC, in_Queens, in_StatenI, in_Westchester, INCTOT, INCWAGE, IND, IND_number,
    LABFORCE, LINGISOL, MARST, MIGCOUNTY1, MIGPLAC1, MIGPUMA1, MIGRATE1, MIGRATE1D, MORTGAGE, NCHILD, NCHLT5, OCC, OWNCOST, OWNERSHP,
    OWNERSHPD, POVERTY, PUMA, PWPUMA00, RACE, race_oth, RACED, RELATE, RELATED, RENT, ROOMS, SCHOOL, SEX, SSMC, TRANTIME, TRANWORK,
    UHRSWORK, UNITSSTR, unmarried, veteran, VETSTAT, VETSTATD, white, WKSWORK2, YRSUSA1

The following objects are masked from dat_use1 (pos = 19):

    AfAm, AGE, Amindian, ANCESTR1, ANCESTR1D, ANCESTR2, ANCESTR2D, Asian, below_150poverty, below_200poverty, below_povertyline, BPL,
    BPLD, BUILTYR2, CITIZEN, CLASSWKR, CLASSWKRD, Commute_bus, Commute_car, Commute_other, Commute_rail, Commute_subway, COSTELEC,
    COSTFUEL, COSTGAS, COSTWATR, Covid_risk, DEGFIELD, DEGFIELD2, DEGFIELD2D, DEGFIELDD, DEPARTS, EDUC, educ_advdeg, educ_college,
    educ_hs, educ_nohs, educ_somecoll, EDUCD, EMPSTAT, EMPSTATD, FAMSIZE, female, foodstamps, FOODSTMP, FTOTINC, FUELHEAT, GQ,
    has_AnyHealthIns, has_PvtHealthIns, HCOVANY, HCOVPRIV, HHINCOME, Hisp_Cuban, Hisp_DomR, Hisp_Mex, Hisp_PR, HISPAN, HISPAND, Hispanic,
    in_Bronx, in_Brooklyn, in_Manhattan, in_Nassau, in_NYC, in_Queens, in_StatenI, in_Westchester, INCTOT, INCWAGE, IND, IND_number,
    LABFORCE, LINGISOL, MARST, MIGCOUNTY1, MIGPLAC1, MIGPUMA1, MIGRATE1, MIGRATE1D, MORTGAGE, NCHILD, NCHLT5, OCC, OWNCOST, OWNERSHP,
    OWNERSHPD, POVERTY, PUMA, PWPUMA00, RACE, race_oth, RACED, RELATE, RELATED, RENT, ROOMS, SCHOOL, SEX, SSMC, TRANTIME, TRANWORK,
    UHRSWORK, UNITSSTR, unmarried, veteran, VETSTAT, VETSTATD, white, WKSWORK2, YRSUSA1

> borough_f <- factor((in_Bronx + 2*in_Manhattan + 3*in_StatenI + 4*in_Brooklyn + 5*in_Queens), levels=c(1,2,3,4,5),labels = c("Bronx","Manhattan","Staten Island","Brooklyn","Queens"))
> 
> norm_varb <- function(X_in) {
+   (X_in - min(X_in, na.rm = TRUE))/( max(X_in, na.rm = TRUE) - min(X_in, na.rm = TRUE) )
+ }
> 
> is.na(OWNCOST) <- which(OWNCOST == 9999999)
> housing_cost <- OWNCOST + RENT
> norm_inc_tot <- norm_varb(INCTOT)
> norm_housing_cost <- norm_varb(housing_cost)
> 
> data_use_prelim <- data.frame(norm_inc_tot,norm_housing_cost)
Error in as.data.frame.default(x[[i]], optional = TRUE) : 
  cannot coerce class ‘"haven_labelled"’ to a data.frame
> good_obs_data_use <- complete.cases(data_use_prelim,borough_f)
> dat_use <- subset(data_use_prelim,good_obs_data_use)
> y_use <- subset(borough_f,good_obs_data_use)
> 
> set.seed(12345)
> NN_obs <- sum(good_obs_data_use == 1)
> select1 <- (runif(NN_obs) < 0.8)
> train_data <- subset(dat_use,select1)
> test_data <- subset(dat_use,(!select1))
> cl_data <- y_use[select1]
> true_data <- y_use[!select1]
> 
> summary(cl_data)
        Bronx     Manhattan Staten Island      Brooklyn        Queens 
         4880          5250          1891         12416         10923 
> prop.table(summary(cl_data))
        Bronx     Manhattan Staten Island      Brooklyn        Queens 
   0.13800905    0.14847285    0.05347851    0.35113122    0.30890837 
> summary(train_data)
  norm_inc_tot     norm_housing_cost
 Min.   :0.00000   Min.   :0.00000  
 1st Qu.:0.01191   1st Qu.:0.02493  
 Median :0.02693   Median :0.96917  
 Mean   :0.04265   Mean   :0.58972  
 3rd Qu.:0.05219   3rd Qu.:0.97784  
 Max.   :1.00000   Max.   :1.00000  
> require(class)
> for (indx in seq(1, 9, by= 2)) {
+   pred_borough <- knn(train_data, test_data, cl_data, k = indx, l = 0, prob = FALSE, use.all = TRUE)
+   num_correct_labels <- sum(pred_borough == true_data)
+   correct_rate <- num_correct_labels/length(true_data)
+   print(c(indx,correct_rate))
+ }
[1] 1.0000000 0.3540087
[1] 3.0000000 0.3437859
[1] 5.0000000 0.3550425
[1] 7.0000000 0.3708936
[1] 9.0000000 0.3721571
> 
> cl_data_n <- as.numeric(cl_data)
> 
> model_ols1 <- lm(cl_data_n ~ train_data$norm_inc_tot + train_data$norm_housing_cost)
> 
> y_hat <- fitted.values(model_ols1)
> 
> mean(y_hat[cl_data_n == 1])
[1] 3.476403
> mean(y_hat[cl_data_n == 2])
[1] 3.375686
> mean(y_hat[cl_data_n == 3])
[1] 3.753125
> mean(y_hat[cl_data_n == 4])
[1] 3.541435
> mean(y_hat[cl_data_n == 5])
[1] 3.62329
> 
> cl_data_n1 <- as.numeric(cl_data_n == 1)
> model_ols_v1 <- lm(cl_data_n1 ~ train_data$norm_inc_tot + train_data$norm_housing_cost)
> y_hat_v1 <- fitted.values(model_ols_v1)
> mean(y_hat_v1[cl_data_n1 == 1])
[1] 0.1592435
> mean(y_hat_v1[cl_data_n1 == 0])
[1] 0.1346093
