# uppaal-smc
the xml file shows a smart building model based on priced timed automata

uppaal version:
4.1.18 on windows or
4.1.19 on linux

##########################################################

usage:
1. the "heater.xml" is uppaal-smc file, so just open it with uppaal and then do some query.

2. two query properties is below or you can see it from the "heater.q" file:

	(1) Pr[<=day](<>energy>=20000000)
	(2) Pr[<=day](<>range_out[1]>=11500)



