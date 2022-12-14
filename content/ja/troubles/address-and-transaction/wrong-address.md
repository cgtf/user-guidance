---
title: "誤った相手先やアドレスに暗号資産を移転してしまった"
linkTitle: "誤った相手先やアドレスに暗号資産を移転してしまった"
weight: 1
date: 2022-11-07T08:00:00+09:00
description: >
  トランザクションはブロックチェーンに取り込まれているようだが、いつまでも送付先のウォレットで暗号資産の残高が確認できない。
---

銀行振込と違い、送金先の相手を確認する手段はアドレスだけであり、名義人を確認することはできません[^1]。また、暗号資産の場合、一度送金が完了すると取り戻す手段は一切ありません[^2]。暗号資産の取引を行う場合には、相手先を十分に確認するようにしましょう。
暗号資産のアドレスは1文字でも間違えると正しい相手に届きません。暗号資産の送付先アドレスを入力する際は、入力間違いのないように、よく確認しましょう。
送付先アドレスの確認と入力するときには、暗号資産を不正に奪うために、アドレスを不正なアドレスに書き換える攻撃があることに注意が必要です[^3]。攻撃者はマルウェア等によって、ブラウザに表示される送付先アドレスの表示を書き換えたり、送付先アドレスの入力欄へのコピーアンドペーストを行う際に入力されるアドレスを改ざんしたりすることがあります。OSやブラウザ、ウイルス対策ソフト等には最新のアップデートを適用し、脆弱性を利用した攻撃を防ぎましょう。
ブラウザに表示されるアドレスの書き換えを防ぐため、Webサイトの情報を変更する権限を必要とするブラウザ拡張機能の利用はなるべく避け、必要な場合にだけ権限を有効にしましょう[^4]。コピーアンドペースト時にアドレスを改ざんしたことに気づかせないために、攻撃者が先頭や末尾の類似したアドレスを用意することも考えられるため、入力した送付先アドレスの確認は最初や最後の一部だけでなく、全体が一致していることを確認することも重要です。
なお、初めて暗号資産を送付するアドレスには、一度少額の暗号資産を送付し、正しく移転することを確かめてから残額を送付することが誤送付の防止に有効です。ウォレットや交換業者が提供する機能として、送付先アドレスを登録しておく「アドレス帳機能」を利用することも有効です。何度か送付するアドレスはアドレス帳に登録しておくことで、誤送付やアドレスの改ざんによる攻撃を防ぐことが出来ます[^5]。

[^1]:Webサイトに表示されるアドレスであったとしても、そのサイトが正しいものであることを確認する必要がありますし、メールで知らされた場合、差出人が正しいことを確認する必要があります。また、相手が誤ったアドレスを記入してしまう可能性もあります。
[^2]:銀行振込の場合、「組戻」という手続きはありますが、振り込み先の承諾がない限り資金を取り戻すことはできません。
[^3]:コインデスク・ジャパン、「新種マルウェア、仮想通貨ウォレットのアドレス入力時に書き換えを行う」、https://www.coindeskjapan.com/24806/、（2022年7月3日時点）
[^4]:Google Chromeは、サイトデータの読み取りと変更を行う権限を拡張機能に与える場合を、すべてのサイト、特定のドメイン、拡張機能をクリックした時の3通りから選択することができます。また、プロフィール機能を利用することでアカウントや利用する拡張機能を切り替えることができます。拡張機能を一切インストールしない、暗号資産を取り扱う際に利用する専用のプロフィールを作成して利用するといった活用方法が考えられます。
[^5]:アドレスが変更された場合、変更後のアドレスを追跡する機能はありませんので、変更の有無については毎回確認する必要があります。

