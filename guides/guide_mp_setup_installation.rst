========================
Руководство по установке
========================

.. title::
   Руководство по установке Particl Desktop & Marketplace

.. meta::
   :description lang=ru: пошагово процедура установки Particl Destop & Marketplace.
   :description lang=en: step by step learn every aspect of the installation of Particl Destop & Marketplace.
   :keywords lang=en: Particl, Marketplace, Installation, Blockchain, Privacy, E-Commerce

В этом разделе вы узнаете как установить торговую площадку :term:`Particl Marketplace`, дополнительное програмное обеспечение и как делать резервные копии ваших данных.

.. contents:: Table of Contents
   :local:
   :backlinks: none
   :depth: 2

Торговая площадка Particl
=========================

Для начала работы с :term:`Particl Marketplace` вам нужно загрузить и установить клиентское ПО :guilabel:`Particl Desktop`. Процедура установки очень простая и не займет более нескольких минут!

Загрузка 
--------

Выбирите нужную вам версию:

.. tabs::
	 .. group-tab:: Windows

	 	**Версии для Windows**

	 	В большинстве случаев будет достаточно загрузить установочный файл :file:`particl-desktop-X.X.X-win.exe`. Он поддерживает любую версию Windows.

	 	**Источники для загрузки**

		- Сайт Particl: https://particl.io/downloads/
		- Particl Github: https://github.com/particl/particl-desktop/releases/latest

		.. attention::

   		 НИКОГДА не загружайте клиентское ПО Particl с посторонних вебсайтов! Злоумышленники постоянно пытаются распространять зараженные вредоносным ПО копии популярных  :term:`криптовалютных <Cryptocurrency>` кошельков с целью украсть ваши деньги! Поэтому всегда загружайте только из официальных источников. 

	 .. group-tab:: Mac

	 	**Версии для MacOS**

	 	В большинстве случаев будет достаточно загрузить установочный файл :file:`particl-desktop-X.X.X-mac.dmg`. Сайт Particl: MacOS, включая 10.15 (Catalina) или выше.

	 	**Источники для загрузки**

		- Сайт Particl: https://particl.io/downloads/
		- Particl Github: https://github.com/particl/particl-desktop/releases/latest

		.. attention::

   		 НИКОГДА не загружайте клиентское ПО Particl с посторонних вебсайтов! Злоумышленники постоянно пытаются распространять зараженные вредоносным ПО копии популярных  :term:`криптовалютных <Cryptocurrency>` кошельков с целью украсть ваши деньги! Поэтому всегда загружайте только из официальных источников. 

	 .. group-tab:: Linux

	 	**Версии для Linux version**

	 	В зависимости от вашего дистрибутива Linux вы можете выбирать между различными пакетами, включая пакеты на базе Debian :file:`.deb`, или пакеты :file:`.rpm`, или независимую от дистрибутива :file:`.AppImage` версию. 

	 	Зная какой дистрибутив Linux вы используете, будет легко определить ваш менеджер пакетов и какой файл вам подойдет. Независимая от дистрибутива :file:`.AppImage` версия сделает установку очень быстро.

	 	**Источники для загрузки**

		- Сайт Particl: https://particl.io/downloads/
		- Particl Github: https://github.com/particl/particl-desktop/releases/latest

		.. attention::

   		 НИКОГДА не загружайте клиентское ПО Particl с посторонних вебсайтов! Злоумышленники постоянно пытаются распространять зараженные вредоносным ПО копии популярных  :term:`криптовалютных <Cryptocurrency>` кошельков с целью украсть ваши деньги! Поэтому всегда загружайте только из официальных источников. 

Процесс установки
-----------------

.. tabs::
	 .. group-tab:: Windows

 		**Установка для Windows**

 		.. rst-class:: bignums

	 		#. :ref:`Проверьте контрольную сумму загруженного файла <Проверка контрольной суммы>`.
	 		#. Запустите загруженный установщик :guilabel:`particl-desktop-X.X.X-win.exe`.
	 		#. Следуйте его инструкциям
	 		#. Иконки приложения будут добавлены на рабочий стол и в меню запуска приложений. Используйте их для старта :term:`Particl Desktop`.
	 		#. Добавьте разрешения в свой брандмауэр и антивирусные программы. В стандартных инсталляциях Windows обычно используется всплывающее окно :guilabel:`Microsoft Defender`.

	 		Игнорирование 5го шага может ухудшить процесс синхронизации блокчейна и он займет больше времени чем обычно, или же  может вызвать проблемы с соединением. Если вы не знаете как устанавливать разрешения для своего брандмауэра и антивирусного ПО - просмотрите документацию поставщика установленных у вас программ.

	 .. group-tab:: Mac

	 	**Установка для MacOS**

	 	.. rst-class:: bignums

	 		#. :ref:`Проверьте контрольную сумму загруженного файла <Проверка контрольной суммы>`.
	 		#. Запустите загруженный установщик :guilabel:`particl-desktop-X.X.X-mac.dmg` нажатием :kbd:`CONTROL` + :kbd:`MOUSE-RIGHT ◳` и кликнув :guilabel:`Open` в появившемся контекстном меню. *Не кликайте по иконке дважды.*
	 		#. Перетащите файл :term:`Particl Desktop.app <Particl Desktop>` в папку :guilabel:`Applications`. 
	 		#. Откройте папку the :guilabel:`Applications` и найдите файл :term:`Particl Desktop.app <Particl Desktop>`. 
	 		#. Нажмите :kbd:`CONTROL` + :kbd:`MOUSE-RIGHT ◳` на :term:`Particl Desktop.app <Particl Desktop>` и затем кликните  :guilabel:`Open`.
	 		#. При первом запуске брандмауэр вашего устройства должен получить правило, разрешающее Particl Desktop взаимодействовать с блокчейном. 

	 	С этого момента вы можете запускать :term:`Particl Desktop` из Launchpad или из поиска Spotlight (т.е. :kbd:`COMMAND ⌘` + :kbd:`SPACE` или набрав "Particl" > hit :kbd:`ENTER ↵` соответственно).

	 .. group-tab:: Linux

	 	**Установка для Linux**

	 	.. rst-class:: bignums

	 		#. :ref:`Проверьте контрольную сумму загруженного файла <Проверка контрольной суммы>`.
	 		#. В терминале перейдите в папку, в которую вы загрузили файл установки.

	 		#. *Следующая команда отличается в зависимости от вашего менеджера пакетов*

	 			**Установка Debian**

	 			.. code-block:: bash

	 				sudo apt install particl-desktop-x.x.x-linux.deb

				**Установка RPM** 

	 			.. code-block:: bash

	 				sudo dnf -i particl-desktop-x.x.x-linux.rpm

	 			**AppImage**

	 			.. code-block:: bash

	 				chmod a+x particl-desktop-x.x.x-linux.AppImage
	 				./particl-desktop-x.x.x-linux.AppImage

	 		#. При первом запуске брандмауэр вашего устройства должен получить правило, разрешающее Particl Desktop взаимодействовать с блокчейном.

	 		Иконка запуска приложения будет добавлена в меню приложений при использовании установок .deb или .rpm. Щелкните ее  чтобы запустить клиент :term:`Particl Desktop`.

	 	.. tip::

	 		Если вы захотите запустить клиент из терминала то имя Particl Desktop нужно заключить в кавычки, т.к. оно содержит пробел.

			.. code-block:: bash
	
				user@linux:~> which "Particl Desktop"
				/usr/bin/Particl Desktop
	
				user@linux:~> "/usr/bin/Particl Desktop"
				(Particl Desktop:16887)

.. rst-class:: achievement

	Поздравляем! Вы установили :term:`Particl Marketplace`.

.. hint::

	**Время загрузки и синхронизации**

	Так как все данные :term:`Particl Marketplace` размещаются в распределенной сети, то потребуется несколько минут для синхронизации прежде чем вы сможете совершать платежи и сделки. Также, возможно потребуется ещё несколько минут для загрузки всех объявлени торговой площадки. Это нормально ожидаемое время, но в будущем эти процессы будут происходить быстрее по мере совершенствования торговой площадки командой Particl.

Проверка контрольной суммы
--------------------------

Код контрольной суммы можно получить из официальных источников загрузки файлов. У каждого файла своя контрольная сумма.

Возможность быть самому себе банком, при этом работая с блокчейн-продуктами, также накладывает на вас и некоторые обязанности. Одна из них - это серьезно относиться к собственной безопасности. Пожалуйста, убедитесь что загруженные вами файлы не были каким-либо образом скомпроментированы, проверив их контрольную сумму.
  
.. tabs::
	 .. group-tab:: Windows

                **Команда проверки контрольной суммы в терминале**
 
	 	.. rst-class:: bignums

	 		#. Откройте :guilabel:`Проводник Windows`
	 		#. Перейдите в папку загрузок и нажмите :kbd:`SHIFT ⇧` + :kbd:`MOUSE-RIGHT ◳`, далее выберите :guilabel:`Открыть командное окно` или :guilabel:`Открыть командную оболочку(powershell)`.
	 		#. Наберите в терминале следующую команду, заменив :file:`имя файла` на реальное и полное имя загруженного вами файла, и нажмите :kbd:`ENTER ↵`.

	 			.. code-block:: bash

	 				CertUtil -hashfile имя файла SHA256

	 .. group-tab:: Mac

	 	**Команда проверки контрольной суммы в терминале**

	 	.. tip::
	 		**Предварительно**: Зайдите в :guilabel:`System Preferences` и выберите :guilabel:`Keyboard` > :guilabel:`Shortcuts` > :guilabel:`Services`. Найдите :guilabel:`New Terminal at Folder` в настройках и отметьте птичкой.

		.. rst-class:: bignums

	 		#. Откройте :guilabel:`Finder`
	 		#. Перейдите в папку, в которую был загружен файл, нажмите :kbd:`MOUSE-RIGHT ◳` и вы увидите опцию :guilabel:`services` > :guilabel:`open terminal` для открытия терминала из этой локации. 
			#. Наберите в терминале следующую команду, заменив :file:`имя файла` на реальное имя загруженного файла.

				.. code-block:: bash

					shasum -a 256 имя файла

	 .. group-tab:: Linux

	 	**Команда проверки контрольной суммы в терминале**

	 	.. rst-class:: bignums

	 		#.  Откройте терминал из в папки, в которую был загружен файл и наберите в терминале следующую команду, заменив :file:`имя файла` на реальное имя загруженного файла.
	 	
	 			.. code-block:: bash

	 				sha256sum имя файла

Как только это сделано, сравните контрольную сумму, полученную в результате описанных выше действий с контрольной суммой, указанной на  официальном источнике загрузок. На скриншоте ниже показан пример поиска этой контрольной суммы(выделено) в разделе :guilabel:`Verification`   репозитория GitHub.

.. figure:: ../_static/media/images/mp_installation_github_checksum_verification.png
    :align: center
    :alt: Контрольная сумма для установки Particl Marketplace
    :target: ../_static/media/images/mp_installation_github_checksum_verification.png

    Контрольная сумма для установки Particl Marketplace

**Решение проблемы при несовпадении контрольной суммы**

Если результат не совпал - попробуйте загрузить файл ещё раз по новой. Также убедитесь что вы его не переименовывали и не разархивировали. Иногда может может быть и так, что ваш антивирус как-то изменяет копируемые файлы - в этом случае найдите свое собственное решение как это отключить.

.. attention::
	
	Если все попытки получить совпадающий номер оказались безуспешны - не устанавливайте :term:`Particl Desktop`, кроме случаев когда вы полностью осознаете что делаете, и попробуйте обратиться в :doc:`службу поддержки Particl <../faq/get_support>` за помощью. 

Запуск Particl Desktop
----------------------

У вас есть два возможных варианта: запуск кликом по иконке(рекомендуется) в меню приложений или командой в терминале.

Запуск из меню приложений 
~~~~~~~~~~~~~~~~~~~~~~~~~

.. tabs::

	.. group-tab:: Windows

	 	**Запуск Particl Desktop из панели приложений**

	 	.. rst-class:: bignums

	 		#. Откройте :guilabel:`Меню Пуск` нажатием кнопки :kbd:`WIN ⊞`
	 		#. Начните набирать слово :code:`Particl`
	 		#. Кликните по иконке запуска :term:`Particl Desktop`.

	.. group-tab:: Mac

	 	**Запуск Particl Desktop из панели приложений**

	 	.. rst-class:: bignums

	 		#. Откройте :guilabel:`Spotlight` (e.g., :kbd:`COMMAND ⌘` + :kbd:`SPACE`) 
	 		#. Наберите :code:`Particl`
	 		#. Кликните по иконке запуска :term:`Particl Desktop`.

	.. group-tab:: Linux

	 	**Запуск Particl Desktop из панели приложений**

	 	.. rst-class:: bignums
	 	
	 		#. Откройте меню приложений.
	 		#. Кликните по иконке запуска :term:`Particl Desktop`.

Запуск из терминала
~~~~~~~~~~~~~~~~~~~

Иногда бывает удобно запускать :term:`Particl Marketplace` из терминала, в режиме командной строки. Это дает вам вывод на экран множества  полезной информации о том, что происходит в фоновом режиме.

.. tabs::

	.. group-tab:: Windows

	 	**Запуск Particl Desktop из терминала**

	 	.. rst-class:: bignums

	 		#. Откройте :guilabel:`Проводник Windows`
	 		#. Нажмите :kbd:`SHIFT ⇧` + :kbd:`MOUSE-RIGHT ◳` в папке приложения(т.е. :file:`C:\/Program Files\/Particl`) и выбирите :guilabel:`Открыть командное окно ` или :guilabel:`Открыть командную оболочку`.
	 		#. Введите следующую команду в терминале и нажмите :kbd:`ENTER ↵`.

	 			.. code-block:: bash

	 				“Particl Desktop.exe”

	.. group-tab:: Mac

	 	**Запуск Particl Desktop из терминала**

	 	.. rst-class:: bignums

	 		#. Откройте :guilabel:`Terminal` (т.е. :kbd:`COMMAND ⌘` + :kbd:`SPACE` и введите "terminal" > нажать :kbd:`ENTER ↵`)
	 		#. Введите эту команду:

				.. code-block:: bash

					/Applications/Particl\ Desktop.app/Contents/MacOS/Particl\ Desktop

	.. group-tab:: Linux

	 	**Запуск Particl Desktop из терминала**

	 	.. rst-class:: bignums
	 	
	 		#. Откройте терминал из папки, в которой установлен :term:`Particl Desktop` и введите следующую команду:
		
				.. code-block:: bash

					./Particl\ Desktop

Резервная копия учетной записи и данных
=======================================

Расположение файлов
-------------------

При успешной установке :term:`Particl Desktop` само главное приложение будет размещено в определенной стандартной папке вашей операционной системы. Кроме этого, при первом запуске :term:`Particl Desktop` создаст некоторые определенные пользовательские данные для вашей учетной записи. Это включает в себя  различные настройки, файлы логов, кошельки и данные блокчейна. Будет очень разумно периодически делать резервную копию всех этих данных и сохранять ее на внешнем носителе в зашифрованном виде.

.. tabs::
	 .. group-tab:: Windows

	 	.. code-block:: bash

	 		## Папки Windows

	 		"%UserProfile%\AppData\Roaming\Particl"
			"%userprofile%\AppData\Roaming\particl-bot"
			"%userprofile%\AppData\Roaming\particl-market"
			"%userprofile%\AppData\Roaming\Particl Desktop"


	 .. group-tab:: Mac

	 	.. code-block:: bash

	 		## Папки MacOS

	 		"~/Library/Application Support/Particl"
			"~/Library/Application Support/particl-bot"
			"~/Library/Application Support/particl-market"
			"~/Library/Application Support/Particl Desktop"

	 .. group-tab:: Linux

	 	.. code-block:: bash

	 		## Папки Linux

	 		"~/.particl"
			"~/.particl-bot"
			"~/.particl-market"
			"~/.config/particl-desktop"

			## Иконка запуска

			"/opt/Particl Desktop/Particl Desktop"

.. seealso::

 Другие источники полезной или более углубленной информации:

 - Particl Вики - `Резервное копирование и восстановление кошелька <https://particl.wiki/tutorial/security/backup-restore-wallet/>`_

Установка Tor (Конфиденциальность в интернете)
==============================================

.. danger::
	
	Всегда следите чтобы ваш :term:`Tor` был обновлен до последней версии. Это важное требование, несоблюдение которого может серьезно навредить вашей конфиденциальности в интернете и потенциально дать возможность другим людям шпионить за вашей деятельностью онлайн.

Единственная настройка конфиденциальности, не включенная по умолчанию - это возможность сохранять анонимность вашего IP-адреса при использовании Particl. Это делается путем маршрутизации соединения вашего клиента через Tor - сетевой протокол, предназначенный для анонимизации вашего IP-адреса.

.. attention::
	
	:term:`Tor` не включен по умолчанию на Particl потому что он требует от вас особого внимания чтобы быть по-настоящему безопасным. Эта сеть работает на вашем компьютере независимо от Particl и это требует от вас понимания основных моментов безопасности. 

Установка и запуск Tor
----------------------

Всегда загружайте Tor только с их официального сайта, для уверенности в том, что вам не попадется какая-нибудь взломанная версия. А иначе что ж  будет хорошего, если установив :term:`Tor`, вы лишь широко распахнете двери для хакеров? 

Для предотвращения `атаки посредника <https://ru.wikipedia.org/wiki/%D0%90%D1%82%D0%B0%D0%BA%D0%B0_%D0%BF%D0%BE%D1%81%D1%80%D0%B5%D0%B4%D0%BD%D0%B8%D0%BA%D0%B0>`_ всегда проверяйте криптографические подписи загружаемых файлов даже если они находятся на официальном сайте :term:`Tor`.

Чтобы сделать это правильно - следуйте руководству этому руководству, написанному непосредственно командой :term:`Tor`: `Как проверить подписи  Tor <https://support.torproject.org/tbb/how-to-verify-signature/>`_ .	

Сеть :term:`Tor` можно установить тремя разными способами. Но, независимо от выбранного вами метода, перед использованием всегда удостоверьтесь что у вас самая последняя версия  :term:`Tor`.

Использование браузера Tor
~~~~~~~~~~~~~~~~~~~~~~~~~~

.. rst-class:: bignums

	#. Загрузите и установите `Tor браузер <https://www.torproject.org/download/>`_ .
	#. Запустите :term:`Tor` браузер.
	#. Соединитесь с сетью :term:`Tor`, кликнув кнопку :guilabel:`Connect`, или же - можно настроить параметры вашего соединения, кликнув :guilabel:`Configure`.
	#. После соединения оставьте :term:`Tor` браузер работать в фоновом режиме.


Использование демона Tor
~~~~~~~~~~~~~~~~~~~~~~~~

.. tabs::

	.. group-tab:: Windows

		**Запуск демона Tor**

		.. rst-class:: bignums

	 		#. Загрузите и установите `Tor браузер <https://www.torproject.org/download/>`_ .
	 		#. Откройте :guilabel:`Проводник Windows` и перейдите в папку, в которой установлен :term:`Tor` (обычно это :file:`C:\/Program Files\/Tor Browser`).
			#. Находясь в папке :file:`Tor`, удерживайте нажатой кнопку :kbd:`SHIFT ⇧` на клавиатуре и кликните правой кнопкой мыши :kbd:`MOUSE-RIGHT ◳`.
			#. Выберите в меню :guilabel:`Открыть командное окно здесь`.
			#. В появившемся терминале наберите команду:

				.. code-block:: bash

					tor.exe –service install

			#. Для проверки что служба :term:`Tor` запущена введите: 
			
				.. code-block:: bash

					sc query "Tor" | find "RUNNING"

	.. group-tab:: Mac

	 	**Запуск демона Tor**

	 	.. tip:: 

	 		Установите Homebrew если он ещё не установлен. Для установки введите этот код в терминале:

	 		.. code-block:: bash 

	 				xcode-select --install
					ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
					echo "export PATH=/usr/local/bin:/usr/local/sbin:$PATH" >> ~/.profile

		.. rst-class:: bignums

			#. Установите демона :term:`Tor` используя Homebrew, введите:

				.. code-block:: bash

					brew install tor

			#. Сделайте :term:`Tor` службой Brew, введите:

				.. code-block:: bash

					brew services start tor

	.. group-tab:: Linux

	 	**Запуск демона Tor**

	 	.. rst-class:: bignums

	 		#. Откройте :guilabel:`терминал`
			#. Установите демона :term:`Tor`, введите:

				.. code-block:: bash 

					sudo apt install tor

			#. Установите запуск :term:`Tor` при загрузке системы, введите: 

				.. code-block:: bash

					sudo systemctl enable tor

Использование Tor как скрытой службы
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

В Linux вы также можете запустить :term:`Tor` как скрытую службу и связать ее с :term:`Particl Desktop`. Такой способ позволит другим людям использовать ваш :term:`узел <Node>` как точку входа или выхода, тем самым делая сеть :term:`Tor` еще более :term:`децентрализованной <Decentralization>` и конфиденциальной.

.. rst-class:: bignums

	#. Откройте a :guilabel:`терминал` и установите сеть :term:`Tor`, введя команду: 
	
		.. code-block:: bash

			sudo apt-get install tor

	#. Установите использование :term:`Tor` как скрытой службы, изменив настройки в файле конфигурации :term:`Tor`. Чтобы это сделать, введите команду: 

		.. code-block:: bash

			sudo nano /etc/tor/torrc

		В открывшийся файл конфигурации добавьте эти две строки:

		.. code-block:: bash

			HiddenServiceDir /var/lib/tor/particl-service/
			HiddenServicePort 51738 127.0.0.1:51738

		Сохраните файл и выйдите из редактора nano, для этого нажмите :kbd:`CTRL+c`, затем введите :kbd:`y` и нажмите :kbd:`ENTER ↵` для сохранения изменений.

	#. Перезапустите :term:`Tor` введя в терминале: 
	
		.. code-block:: bash
		
			sudo service tor restart

	#. Найдите IP адрес(.onion) вашей скрытой службы (в этом руководстве далее мы будем называть этот адрес как :code:`[yourexternalip].onion`). Для этого введите:
	
		.. code-block:: bash

			sudo cat /var/lib/tor/particl-service/hostname

	#. Измените файл конфигурации Particl, чтобы маршрутизировать его соединение через скрытую службу, введите: 

		.. code-block:: bash

			touch ~/.particl/particl.conf && nano ~/.particl/particl.conf

		Затем добавьте эти строки в файл и не забудьте указать свой :code:`yourexternalip.onion` 

		.. code-block:: bash
	
			externalip=[yourexternalip].onion
			onion=127.0.0.1:9050
			addnode=7vusex6gv5eerqi2.onion
			addnode=quf7tm4gk3xn3aee.onion
			addnode=46fvsrrq75dx5vq4.onion
			addnode=ciikdjtoop7l6p6h.onion
			addnode=frlfghlielxq2ncy.onion
			addnode=partusq5qad6jd2c.onion
			addnode=x6fxdwpq2krxzmr3.onion
			addnode=amu2ck7lyw26fiqs.onion
			addnode=kfyopkn3shigcneh.onion
			onlynet=tor
			listen=1
			bind=127.0.0.1:51738
			maxconnections=30

		Сохраните файл и выйдите из редактора nano, для этого нажмите :kbd:`CTRL+c`, затем введите :kbd:`y` и нажмите :kbd:`ENTER ↵` для сохранения изменений.

Включить Tor на Particl
-----------------------

Все, что вам нужно сделать для включения :term:`Tor` на Particl - это запустить :term:`Particl Desktop` с правильными настройками. Можно или добавить специальный параметр в команду, используемую для запуска Particl, или же сделать постоянные настройки.

Включить по умолчанию в GUI
~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. rst-class:: bignums

	#. Запустите :term:`Particl Desktop` и кликните :guilabel:`Particl Desktop Settings`, в левом нижнем углу
	#. Зайдите в :guilabel:`Core network connection` и в поле :guilabel:`Connect via Proxy` введите: :code:`127.0.0.1:9150`
	#. Нажмите :guilabel:`Save changes` и перезапустите :term:`Particl Desktop`

Включить по умолчанию в CLI
~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. rst-class:: bignums

	#. Откройте файл конфигурации: 

		.. code-block:: bash

			nano ~/.particl/particl.conf

	#. Добавьте эту строку в файл:

		.. code-block:: bash

			proxy=127.0.0.1:9150

.. note::

	С этого момента :term:`Particl Desktop` будет пытаться установить интернет соединение, используя эти параметры. Это означает, что если :guilabel:`Tor` не будет запущен на вашем компьютере, то и :term:`Particl Desktop` не будет иметь доступа к интернету.

Включить при запуске из терминала
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. tabs::

	.. group-tab:: Windows

	 	**Запуск Particl с Tor**

	 	.. rst-class:: bignums

                        #. Откройте :guilabel:`Проводник Windows` и нажмите :kbd:`SHIFT ⇧` + :kbd:`MOUSE-RIGHT ◳` в папке приложения(обычно :file:`C:\/Program Files\/Particl`), далее выберите :guilabel:`Открыть командное окно` или :guilabel:`Открыть командную оболочку(powershell)`.
	 		#. Введите в терминале следующую команду, затем нажмите :kbd:`ENTER ↵`:

	 			.. code-block:: bash

	 				“Particl Desktop.exe” -proxy=127.0.0.1:9150

	.. group-tab:: Mac

	 	**Запуск Particl с Tor**

	 	.. rst-class:: bignums

	 		#. Откройте :guilabel:`Terminal` (т.е. :kbd:`COMMAND ⌘` + :kbd:`SPACE` введите "terminal" >нажмите :kbd:`ENTER ↵`)
	 		#. Введите эту команду:

				.. code-block:: bash

					/Applications/Particl\ Desktop.app/Contents/MacOS/Particl\ Desktop -proxy=127.0.0.1:9150

	.. group-tab:: Linux

	 	**Запуск Particl с Tor**

	 	.. rst-class:: bignums
	 	
	 		#. Откройте терминал из папки, в которой установлен :term:`Particl Desktop` и введите следующую команду:
		
				.. code-block:: bash

					./Particl\ Desktop -proxy=127.0.0.1:9150


Внимание, это важно!
--------------------

Поддерживайте Tor обновленным
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

:term:`Tor` необходимо всегда обновлять до последней версии. Это важное требование, несоблюдение которого может серьезно навредить вашей конфиденциальности в интернете. Обновления :term:`Tor` содержат очень важные исправления безопасности, обеспечивающие конфиденциальность вашей личности.

Поскольку сеть сама по себе широко используется хакерами из-за той конфиденциальности, которую она обеспечивает, то непропатченные версии :term:`Tor` считаются небезопасными для использования. В случае взлома скомпрометированная версия :term:`Tor` может привести к утечке вашей реальной личности и даже позволить другим шпионить за вашей активностью онлайн. 

.. tabs::
	 .. group-tab:: Windows

	 	**Обновление Tor**

	 	.. rst-class:: bignums

	 		#. Запустите the :term:`Tor` браузер
	 		#. Проверьте, не предлагает ли вам браузер обновить версию до более новой. 

	 .. group-tab:: Mac

	 	**Обновление Tor**

	 	.. rst-class:: bignums

	 		#. Откройте :guilabel:`Terminal` (т.е., :kbd:`COMMAND ⌘` + :kbd:`SPACE` и введите "terminal" > нажмите :kbd:`ENTER ↵`)
	 		#. Ввведите эту строку кода и нажмите :kbd:`ENTER ↵`

	 			.. code-block:: bash
	
	 				brew update && brew upgrade

	 .. group-tab:: Linux

	 	**Обновление Tor**

	 	.. rst-class:: bignums

	 		#. Откройте a :guilabel:`терминал` и запустите процедуру обновления, в зависимости от используемого менеджера пакетов.

	 			**Например:**

	 			.. code-block:: bash

	 				sudo apt update && sudo apt-upgrade

	 	В зависимости от вашего дистрибутива Linux эта команда может отличаться. Есть несколько менеджеров пакетов, но их использование практически одинаково.


