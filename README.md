﻿# AnemunTelegramBots-Late

Бот предназначен для небольших команд/офисов и позволяет собирать статистику по переработкам/опозданиям.
Любой пользователь может прислать боту сообщение в формате "<время> <комментарий>", и оно будет записано в базу для последующей статистики.
Если послать время со знаком плюс, например, "+15 дорабатывал заявку", то в базу будет записана переработка в 15 минут с соответсвующим комментарием.
Если послать время со знаком минус, то будет, соответственно, записано опоздание (например, "-20 пробки на дороге").

Для запуска бота надо запустить "AnemunLateBot.py <токен бота> <путь к файлу базы данных>".
Если файла нет по указанному пути, он будет создан.

По команде /help будут доступны различные команды для вывода статистики.

Бот никак не защищён от вмешательства извне и изнутри компании, используйте его на свой страх и риск.
