﻿=== Manueller Datenexport von WooCommerce nach Lexware ===
Contributors: Odido
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_xclick&business=owagner@verizon-press.de&item_name=WooCommerce2Lexware&currency_code=EUR
Tags: export, order, woocommerce, lexware, opentrans, xml
Requires at least: WooCommerce 2.3.5
Tested up to: 4.3.1
Stable tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Exports not yet exported orders from woocommerce to a xml-file for Lexware - format is openTRANS.

== Description ==

= Scan & Notify =
*WooCommerce to Lexware* exports orders from woocommerce. All exported orders are tagged in the database so they won't be exported again. The export file is a xml corresponding to the <a href="https://support.lexware.de/support/produkte/warenwirtschaft-pro/fragen-und-antworten/000000000047110?">specifications  described</a> by Lexware. The export files are named with this pattern: yyyymmdd-hhmmss.xml and are stored in the directory /export.

= Requirements =
* WooCommerce 2.3.5 - 2.4.7
* WordPress

= Donation =
* [PayPal](https://www.paypal.com/cgi-bin/webscr?cmd=_xclick&business=owagner@verizon-press.de&item_name=WooCommerce2Lexware&currency_code=EUR)

= Documentation =
* [Bestellexport](http://www.ad-libitum.info/plugins/adlib-bestellexport-manuell "Bestellexport") (DE)

== Frequently Asked Questions ==

= Wenn ich die Exportdatei öffne, werden statt der Umlaute kryptische Zeichen angezeigt. =

In diesem Fall ist in dem Editor, der die Datei anzeigt, der falsche Zeichensatz eingestellt. Stellen Sie auf UTF-8 um und die Umlaute werden korrekt dargestellt.

== Screenshots ==

1. The dialog of WooCommerce to Lexware

== Changelog ==

= 0.1 =
woo2lex is published

= 0.2 =
i18n added

= 0.2.1 =
new encoding: UTF-8