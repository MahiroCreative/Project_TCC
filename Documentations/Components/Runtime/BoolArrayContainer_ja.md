﻿# BoolArrayContainer

#### **Namespace**: Unity.SaveData
---

## 概要:
`BoolArrayContainer` は、`bool` 配列を保存するための具体的な `DataContainerBase<bool[]>` の実装です。このコンポーネントを使用することで、複数のブール値を一つのデータコンテナとして管理し、永続化することができます。

## 主な特徴:
- **ブール配列の保存**: `bool` 型の配列を保存し、必要に応じてアクセスおよび更新が可能です。
- **データ識別**: 一意の ID (`PropertyName`) を使用して、データコンテナを識別します。

## 使用例:
- `BoolArrayContainer` コンポーネントをゲームオブジェクトに追加します。
- Unity エディタで、コンポーネントに保存したい `bool` 配列のデータを設定します。
- ゲーム内で `Value` プロパティを通じてブール配列にアクセスし、必要に応じて値を読み書きします。

---
## 追加情報:
- `BoolArrayContainer` は、ゲームの設定オプションや状態フラグなど、複数のブール値を一括で管理する必要がある場合に特に便利です。
- `DataContainerBase<bool[]>` から継承しているため、`SaveDataControl` システムを使用して簡単に保存および読み込みを行うことができます。

`BoolArrayContainer` は、ブール値の配列を効率的に管理し、ゲーム開発におけるデータ管理の柔軟性を高めるためのシンプルで効果的なソリューションを提供します。