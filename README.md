# RFM-analysis
RFM анализ - инструмент маркетинга для сегментации клиентской базы.

Код анализа в файле https://github.com/suleymanovan/RFM-analysis/blob/main/RFM_analysis.ipynb

Я присвоила каждому клиенту степень «1», «2», «3» в зависимости от:
1. общей суммы оплаченных заказов за весь период - показатель Monetary (M)
2. частоты заказов – Frequency (F)
3. насколько недавно была совершена последняя сделка – Recency (R)

Это сегментирование можно применять для целей таргетинга, имейл-рассылок, обзвонов, спец. предложений и других маркетинговых активностей.

Расшифровка комбинаций RFM:

111 - недавние частые с высоким чеком

112 - недавние частые со средним чеком

113 - недавние частые с низким чеком

121 - недавние редкие с высоким чеком

122 - недавние редкие со средним чеком

123 - недавние редкие с низким чеком

131 - недавние разовые с высоким чеком

132 - недавние разовые со средним чеком

133 - недавние разовые с низким чеком

211 - давние частые с высоким чеком

212 - давние частые со средним чеком

213 - давние частые с низким чеком

221 - давние редкие с высоким чеком

222 - давние редкие со средним чеком

223 - давние редкие с низким чеком

231 - давние разовые с высоким чеком

232 - давние разовые со средним чеком

233 - давние разовые с низким чеком

311 -  очень давние частые с высоким чеком (больше года назад)

312 - очень давние частые со средним чеком (больше года назад)

313 - очень давние частые с низким чеком (больше года назад)

321 - очень давние редкие с высоким чеком

322 - очень давние редкие со средним чеком

323 - очень давние редкие с низким чеком

331 - очень давние разовые с высоким чеком

332 - очень давние разовые со средним чеком

333 - очень давние разовые с низким чеком
