# π°π·π«π· λ§κ΅­λ°λν πΊπΈπ¦πΉ

## λͺ©μ°¨
1. [μκ°](#-μκ°)
2. [νμ](#-νμ)
3. [νμλΌμΈ](#-νμλΌμΈ)
4. [UML](#-UML)
5. [μ€ν νλ©΄](#-μ€ν-νλ©΄)
6. [νΈλ¬λΈ μν](#-νΈλ¬λΈ-μν)
7. [ν΅μ¬ κ²½ν](#-νλ‘μ νΈ-μν-μ€-ν΅μ¬-κ²½ν)
8. [μ°Έκ³  λ§ν¬](#-μ°Έκ³ -λ§ν¬)

## 1. μκ°
- 1900λμ νλμ€ νλ¦¬μμ μ΄λ¦° λ§κ΅­λ°λνμ λν μκ°μ, νκ΅­μ μΆνμμ λν΄ μμλ³Ό μ μλ μ±μλλ€.  

<br>

## 2. νμ
|Ayaan | bella |
| --- | --- |
|<img src= "https://i.imgur.com/Unq1bdd.png" width ="155"/>| <img src=https://user-images.githubusercontent.com/99257965/190572701-5e51fd28-455f-4c3b-924d-0baade5011a3.png width="155" height="155" > |
| [@oneStar92](https://github.com/oneStar92) | [@hyhy0429](https://github.com/hyhy0429) |

<br>

## 3. νμλΌμΈ
**[STEP-1]**
- 221018
    - JSON μ΄ν΄μ νμ©
    - Assetμ μ΄λ―Έμ§μ JSON λ°μ΄ν° μΆκ° ν, ν΄λΉ λ°μ΄ν°λ₯Ό μ¬μ©νκΈ° μν `ExpositionUniverselle` νμκ³Ό `ExpositionUniverselleItem` νμ μΆκ°
- 221019
    - `ExpositionUniverselleItem` νμ μ­νμ λ§κ² λ¦¬ν©ν λ§
  
**[STEP-2]**
- 221020
    - Main(μ²«λ² μ§Έ) νλ©΄ UI κ΅¬μ±μμ κ΅¬ν
    - MainVC λ΄λΆ νμ νλ‘νΌν°μ λ©μλ κ΅¬ν
    - `ExpositionItems` λλ² μ§Έ νλ©΄ UI κ΅¬μ±μμ κ΅¬ν
    - `ExpositionItemsVC` λ΄λΆ νμ νλ‘νΌν°μ λ©μλ κ΅¬ν
    - `ExpositionItemDetail` μΈλ² μ§Έ νλ©΄ UI κ΅¬μ±μμ κ΅¬ν
- 221021
    - `ExpositionItemDetailVC` λ΄λΆ νμ νλ‘νΌν°μ λ©μλ κ΅¬ν
    - κ° νλ©΄μ λ§λ `NavigationBar` μν κ΅¬ν
    - `NameSpace` κ΅¬ν
    - `JSONProcessor` κ΅¬ν
    - MainVC λ° Detail λ΄λΆ TextView μμΈ μ€μ 
- 221025
    - VC `final`, `super` ν€μλ μ¬μ©
    - `JSONProcessor`μ κΈ°λ₯λΆλ¦¬μ λ€μ΄λ° μμ 
    - JASONParser λ΄λΆ fetchDataAsset λ©μλ μΆκ°
    - λΆνμν extensionμ MARK μ£ΌμμΌλ‘ λ³κ²½
    - MainVCμ ExpositionItemDetailVC λ΄λΆμ TextViewλ₯Ό Labelλ‘ λ³κ²½

**[STEP-3]**
- 221026
    - MainView λ΄λΆ μ€ν λ μ΄μμ μμ 
    - `ExpositionItemCell` κ΅¬ν
    - Dynamic Typeμ μν UILabel extension κ΅¬ν
- 221027
    - Main νλ©΄ μκ΅¬μ¬ν­μ λ§λ Label μ€νμΌ κ΅¬ν
    - MainVC `visitorLabel`μ μν `DecimalNumberFormatter` νμΌ μμ±κ³Ό νμ κ΅¬ν
    - Labelμ `Dynamic Type` ν΄μ λλ λ²κ·Έ μμ 
    - Main νλ©΄ μΈλ‘ κ³ μ  κ΅¬ν
    - λͺ¨λ  VCμμ overrideλ₯Ό ν΅ν `supportedInterfaceOrientations` νλ‘νΌν° κ΅¬ν
- 221028
    - MVC μ­ν  λΆλ°°λ₯Ό μν `MainViewManager` νμ κ΅¬ν

<br>

## 4. UML
<img src="https://i.imgur.com/IFXc1gS.jpg" width="800" height="500"/>

## 5. μ€ννλ©΄

|μ€ν νλ©΄|λ€μ΄λλ―Ή νμ|
|:---:|:---:|
|<img src="https://i.imgur.com/77SkGR0.gif" width="400" height="400"/>|<img src="https://i.imgur.com/gb03T08.gif" width="200" height="400"/>|


## 6. νΈλ¬λΈ μν

#### DTO Typeμ νλ‘νΌν° μ κ·Ό μ μ΄μ
- DTOμ νλ‘νΌν°μ μ κ·Ό μ μ΄μλ₯Ό `private(set)`κ³Ό `let` λκ°μ§ μ€μμ λ¬΄μμ μ¬μ©ν΄μΌ ν μ§ κ³ λ―Όνμ΅λλ€.
- `private(set)`μ κ²½μ° λ΄λΆμμλ λ³κ²½μ΄ κ°λ₯νλ `let`μ κ²½μ° μ΄λμλΌμ΄μ§ μ΄ν λ΄/μΈλΆμμ λ³κ²½μ΄ λΆκ°λ₯νκΈ° λλ¬Έμ DTO Typeμ νλ‘νΌν° μ κ·Ό μ μ΄μλ `let`μΌλ‘ μ μΈνλ κ²μ΄ λ μ¬λ°λ₯΄λ€κ³  μκ°ν΄ `let`μ μ¬μ©νμμ΅λλ€.

#### Main νλ©΄ κ΅¬μ±μ, TextView μ¬μ© vs label μ¬μ©
- μ²«λ²μ§Έ νλ©΄μΈ Main νλ©΄μμ, ExpositionUniverselle DTOμ μ₯λ¬Έμ textμΈ descriptionμ κ΅¬ννκΈ° μν UI κ΅¬μ±μμλ₯Ό κ΅¬μ±ν¨μ μμ΄μ `TextView`μ `Label` μ¬μ©μ λν΄μ κ³ λ―Όνμ΅λλ€.
 `Apple HIG` μ κ° λ¬Έμμ [Displaying Text Content in iOS](https://developer.apple.com/library/archive/documentation/StringsTextFonts/Conceptual/TextAndWebiPhoneOS/UsingTextClasses/UsingTextClasses.html)λ₯Ό μ°Έκ³ νμμ΅λλ€. ν¬κ² `label`μ μλμ textλ₯Ό λ³΄μ¬μ£Όλ©° νΈμ§ν  μ μλ μ κ³Ό, `TextView` λ λ€λμ textλ₯Ό λ³΄μ¬μ£Όλ©° νΈμ§μ μ νμ΄ κ°λ₯νλ€λ μ μ΄ μμμ΅λλ€. 
κ·ΈλΌμλ λΆκ΅¬νκ³ , μ ν¬λ λ€λμ textλ₯Ό λ³΄μ¬μ£Όλ κ²μ μ°μ μμλ‘ μκ°νμ¬ `TextView` λ₯Ό μ ννμ¬ κ΅¬ννμλ€κ°, νμ¬ νλ‘μ νΈ μν©κ³Ό λ¬λ¦¬ `editable` κΈ°λ₯μ νμλ‘ ν  λμ `TextView`λ₯Ό μ¬μ©ν΄μΌ ν¨μ λν΄ μκ²λμκ³ , `label`λ‘ λ³κ²½νκ² λμμ΅λλ€. 

#### Segueλ₯Ό ν΅ν νλ©΄ μ νμ λ°μ΄ν° μ μ‘.
- Segueλ₯Ό μ΄μ©νμ¬ μ€ν λ¦¬λ³΄λμμ νκ΅­μ μΆνμμ λ³΄μ¬μ£Όλ TableViewμ Cellμ ν΄λ¦­νλ©΄, ν΄λ¦­λ Cellμ ν΄λΉνλ μΆνμμ μμΈ μ λ³΄λ₯Ό λ³΄μ¬μ£Όλ Viewλ‘ νλ©΄μ νμ΄ λκ² κ΅¬ννμμ΅λλ€. `prepare()`λ©μλλ₯Ό μ€λ²λΌμ΄λνμ¬ λ°μ΄ν°λ₯Ό μ μ‘ν λ, `sender`λ‘ μ λ¬λλ μμΈ μ λ³΄λ₯Ό λνλ΄λ λ°μ΄ν°κ° cellμλ μκΈ° λλ¬Έμ μμΈ μ λ³΄λ₯Ό λ³΄μ¬μ£Όλ Viewμ μ¬λ°λ₯Έ λ°μ΄ν°λ₯Ό μ μ‘νμ§ λͺ»νλ λ¬Έμ κ° λ°μνμμ΅λλ€.
- TableView Delegateμ λ©μλμΈ `tableView(_ tableView: UITableView, didSelectRowAt indexPath: IndexPath)`λ₯Ό μ¬μ©ν΄ μμΈ μ λ³΄λ₯Ό λ³΄κ³ μΆμ Cellμ μ ννλ©΄ μ νλ μμ rowμ ν΄λΉνλ Itemμ `performSegue`λ©μλμ `sender`λ‘ μ λ¬ν΄ μ£Όμ΄μ ν΄λΉ λ¬Έμ λ₯Ό ν΄κ²°νμμ΅λλ€.
```swift
func tableView(_ tableView: UITableView, didSelectRowAt indexPath: IndexPath) {
    self.performSegue(withIdentifier: "ShowItemDetail", sender: expositionItems[indexPath.row])
}

override func prepare(for segue: UIStoryboardSegue, sender: Any?) {
    guard let nextViewController: ExpositionItemDetailViewController = segue.destination as? ExpositionItemDetailViewController,
          let item: ExpositionUniverselleItem = sender as? ExpositionUniverselleItem else {
        return
    }
    
    nextViewController.item = item
}
```

#### λ©μΈνμ΄μ§ μ΄λλ²νΌ
|Before|After|
|:---:|:---:|
|<img src="https://i.imgur.com/op4N0rw.gif" width="200" height="400"/>|<img src="https://i.imgur.com/wHQ3Eqn.gif" width="200" height="400"/>|

```swift
showKoreanItemListButton.titleLabel?.text = "νκ΅­μ μΆνμ λ³΄λ¬κ°κΈ°"
``` 
- MainVC λ΄λΆμμ λ€μ νλ©΄μΌλ‘ μ΄λνκΈ° μν΄ ν΄λΉ μ½λλ₯Ό μ΄μ©ν΄ μνλ textλ₯Ό κ΅¬νμ νμμΌλ, λ²νΌμ ν΄λ¦­νλ©΄ λ²νΌμ ν΄λ¦­ν νμ νλ©΄ μ΄λ ν λ€μ Main νλ©΄μΌλ‘ λλμμμ λ μ§μ ν textκ° μλ λ²νΌμ΄ κ°μ§κ³  μλ μλμ textμΈ "Button" μ΄ λ³΄μ¬μ§λ λ¬Έμ κ° μμμ΅λλ€.

```swift
showKoreanItemListButton.setTitle("νκ΅­μ μΆνμ λ³΄λ¬κ°κΈ°", for: .normal)
```
- Buttonμ Stateκ° `.nomal`μΌλμ Titleμ΄ "Button"μ΄μ¬μ λ°μνλ κ²μΌλ‘ νμνμΌλ©°, Buttonμ `titleLabel`μ `text`λ₯Ό μ§μ  λ°κΎΈλ λ°©μμ΄ μλ `setTitle(_,for:)`λ©μλλ₯Ό μ¬μ©νμ¬ λ²νΌμ Stateμ λ°λ₯Έ Titleμ μ§μ ν΄μ€μ ν΄κ²°νμμ΅λλ€.

#### Label μ€μ κ³Ό Dynamic Type
- MainViewμ Labelμ font, textAlignment, numberOfLines, lineBreakMode λ±μ Labelμ μ€μ μ ν  λ, μ½λλ₯Ό μ€λ³΅ν΄μ μμ±νκ² λμμ΅λλ€.
- μ€λ³΅λ μ½λλ₯Ό μ€μ΄κ³ μ Inheritance λ° Extentionμ νμ©νμ¬ μ€λ³΅λ μ½λλ₯Ό μ€μμ΅λλ€.

#### Main VCμ Labelμ μλ‘λ€λ₯Έ Font μ μ©
- `range`μ λ²μλ₯Ό μ΄λ»κ² μ§μ ν΄μ£Όμ΄μΌ ν μ§μ λν κ³ λ―Όμ΄ μμκ³ , String Typeμ λ©μλμΈ `prefix`λ₯Ό μ¬μ©ν΄μ μ§μ ν΄ μ€ μ μμμ΅λλ€.
- κΈ°λ³Έμ μΈ Fontλ₯Ό Dynamic TypeμΌλ‘ μ€μ ν ν, μνλ λ²μμ attributedTextλ₯Ό μ§μ ν΄μ€¬μ΅λλ€. νμ§λ§ attributedTextκ° μ§μ λ λ²μ μ΄μΈμ Textλ Dynamic Typeμ΄ μλ μ²μ μ€μ λ Fontλ‘ κ³ μ λλ μ€λ₯κ° λ°μνμ΅λλ€.
- μ μ²΄ λ²μμ attributedTextλ₯Ό μ§μ ν΄ μ€ ν μνλ λ²μμ attributedTextλ₯Ό μΆκ°μ μΌλ‘ μ§μ ν΄ μ€μ μ΄λ₯Ό ν΄κ²°νμμ΅λλ€.

#### Title Label μ€λ°κΏ
- Title Labelμ μ€λ°κΏνκΈ° μν΄μ μ κ·μ μ¬μ©μ κ³ λ―Ό νμμ§λ§, λλ¬΄ λ¬΄κ±°μ΄ λ΄μ©μ΄λΌκ³  μκ°λμ΄ λ€λ₯Έ λ°©λ²μ κ³ λ―Όνμ΅λλ€.
- κ³ λ―Ό λμ, Title Labelμ textμμ μ€λ°κΏ νκ³ μ νλ λΆλΆμΈ '('μ indexλ₯Ό κ΅¬ν ν, `inset(_, at:)`λ©μλλ₯Ό μ΄μ©ν΄μ μνλ index λΆλΆμ '\n'λ₯Ό insert νμ΅λλ€.

#### κ° νλ©΄μ κ³ μ  λ°©ν₯ μ§μ 
- AppDelegateμμ νλ©΄ λ°©ν₯ κ³ μ νλ λ°©λ²λ μλ κ²μ μμμ§λ§, μμ§ AppDelegateμ λν κ³΅λΆκ° λΆμ‘±νλ€κ³  μκ°νμ΅λλ€. κ·Έλμ View Controllerμ `supportedInterfaceOrientations` νλ‘νΌν°λ₯Ό μ΄μ©ν΄ νλ©΄ λ°©ν₯μ κ³ μ νλλ‘ κ΅¬ννμμ΅λλ€.

#### Viewλ₯Ό κ΄λ¦¬νλ κ°μ²΄ κ΅¬ν
- λ¦¬λ·°μ΄μ ν μν ν VCλ Viewμ κ°κΉκ³  λ°μ΄ν°λ₯Ό μ²λ¦¬νκ³  κ°κ³΅νλ λ±μ λ‘μ§μ κ΄ν λ΄μ©μ μ νμκ° μλ€λ κ²°λ‘ μ μ»μμ΅λλ€.
- MainVCμμ μ²λ¦¬νλ λ‘μ§μ κ΄λ¦¬νλ `MainViewManager`κ°μ²΄λ₯Ό κ΅¬ννμ¬ ν΄λΉ λ¬Έμ λ₯Ό ν΄κ²°νμ΅λλ€.

#### MainViewManagerμ λ°μ΄ν° μ²λ¦¬ λ‘μ§ λ°©λ²
- `MainViewManager`κ°μ²΄μ μ μ₯λκ³  λΆλ¬μ€λ λ‘μ§μ λ©μλλ₯Ό ν΅ν΄μ κ΅¬ννλ €κ³  νμ΅λλ€. λ©μλλ₯Ό ν΅ν΄ κ΅¬ννκ² λλ©΄ κ°μ²΄μ λ§μ λ©μλλ₯Ό κ°μ§λ λ¬Έμ κ° λ°μνμ΅λλ€.
- μ μ₯ νλ‘νΌν°μ μ°μ° νλ‘νΌν°λ₯Ό λ°λ‘ κ΅¬νν΄ λ°μ΄ν°λ₯Ό μ μ₯ν  λ μ°μ° νλ‘νΌν°μ `set`μ μ΄μ©νμ¬ μ μ₯ νλ‘νΌν°μ μνλ λ‘μ§μ κ²°κ³Όλ₯Ό μ μ₯νλλ‘ κ΅¬ννμκ³ , μ°μ° νλ‘νΌν°μ `get`μ ν΅ν΄ μ μ₯νλ‘νΌν°μ λ°μ΄ν°λ₯Ό μνλ ννλ‘ λΆλ¬μ€κ² κ΅¬ννμ΅λλ€.

<br>

## 7. νλ‘μ νΈ μν μ€ ν΅μ¬ κ²½ν

- JSON μ΄ν΄μ νμ©
- ScrollVeiwμ μ΄ν΄μ νμ©
- tableViewμ Cellμ μ΄ν΄μ νμ©
- νλ©΄ κ° λ°μ΄ν° μ λ¬ 
- lldb νμ©
- λ€μν κΈ°κΈ°μ λμν  μ μλ μ€ν  λ μ΄μμμ μ μ©
- Word Wrapping, Line Wrapping, Line Break λ°©μμ μ΄ν΄ λ° νμ©
- Dynamic Typesμ μ μ©ν΄ νμ€νΈ μ κ·Όμ± ν₯μ

<br>

## 8. μ°Έκ³  λ§ν¬
- Apple Developer 
    - [UITableView](https://developer.apple.com/documentation/uikit/uitableview)
    - [Table views](https://developer.apple.com/documentation/uikit/views_and_controls/table_views)
    - [Filling a table with data](https://developer.apple.com/documentation/uikit/views_and_controls/table_views/filling_a_table_with_data)
    - [UIControl.State](https://developer.apple.com/documentation/uikit/uicontrol/state)
    - [Configuring the cells for your table](https://developer.apple.com/documentation/uikit/views_and_controls/table_views/configuring_the_cells_for_your_table)
    - [JSONDecoder](https://developer.apple.com/documentation/foundation/jsondecoder)
        - [Using JSON with Custom Types](https://developer.apple.com/documentation/foundation/archives_and_serialization/using_json_with_custom_types)
        - [Encoding and Decoding Custom Types](https://developer.apple.com/documentation/foundation/archives_and_serialization/encoding_and_decoding_custom_types)
    - [HIG - Text views](https://developer.apple.com/design/human-interface-guidelines/components/content/text-views)
    - [HIG - View](https://developer.apple.com/design/human-interface-guidelines/components/layout-and-organization/labels)
    - [Displaying Text Content in iOS](https://developer.apple.com/library/archive/documentation/StringsTextFonts/Conceptual/TextAndWebiPhoneOS/UsingTextClasses/UsingTextClasses.html)
    - [NSAttributedString](https://developer.apple.com/documentation/foundation/nsattributedstring)
    - [HIG - Typography](https://developer.apple.com/design/human-interface-guidelines/foundations/typography)

---
[π λ§¨ μλ‘ μ΄λνκΈ°](#λ§κ΅­λ°λν)

