
# pnk-react-native-select

A customizable, cross-platform **select (picker)** component for **React Native**. Supports both **iOS and Android** platforms, with native UI behavior, **modal picker on iOS**, and optional **multi-select** support.

Perfect for forms, dropdowns, and mobile UIs where a clean, native experience is important.

---

## 🚀 Features

- ✅ Single and Multiple Select Support
- ✅ Disabled State Support
- ✅ Modal Picker for iOS
- ✅ Inline Picker for Android
- ✅ Cross-platform Styling
- ✅ Simple API and Easy Integration

---

## 📦 Installation

```bash
npm install pnk-react-native-select @react-native-picker/picker
# or
yarn add pnk-react-native-select @react-native-picker/picker
```

---

## 🔧 Props

| Prop       | Type               | Description                                      |
|------------|--------------------|--------------------------------------------------|
| `label`    | `string`           | Label shown above the picker                    |
| `value`    | `string` or `string[]` | Selected value(s)                            |
| `onChange` | `function`         | Callback when selection changes                 |
| `options`  | `Array<{ label, value }>` | Picker options                            |
| `multiple` | `boolean`          | Enables multiple selection                      |
| `disabled` | `boolean`          | Disables the picker                             |

---

## 📋 Usage

### ✅ Single Select (Default)

```jsx
import PnkSelect from 'pnk-react-native-select';

<PnkSelect
  label="Choose a fruit"
  value={fruit}
  onChange={setFruit}
  options={[
    { label: 'Apple', value: 'apple' },
    { label: 'Banana', value: 'banana' },
    { label: 'Mango', value: 'mango' },
  ]}
/>
```

### ✅ Multi Select

```jsx
<PnkSelect
  label="Choose multiple fruits"
  value={selectedFruits}
  onChange={setSelectedFruits}
  multiple
  options={[
    { label: 'Apple', value: 'apple' },
    { label: 'Banana', value: 'banana' },
    { label: 'Grapes', value: 'grapes' },
  ]}
/>
```

### ✅ Disabled Picker

```jsx
<PnkSelect
  label="Select (disabled)"
  value={fruit}
  onChange={setFruit}
  disabled
  options={[
    { label: 'Apple', value: 'apple' },
    { label: 'Banana', value: 'banana' },
  ]}
/>
```

---

## 💡 Why Use This Component?

If you're building a React Native form or app and need a flexible picker that:

- Works well on both iOS and Android
- Supports multiple selection
- Supports custom styling and behavior

Then `pnk-react-native-select` is for you.

---

## 🔗 Related Keywords

> React Native Picker, React Native Select, React Native Dropdown, iOS Picker, Android Picker, Modal Picker, Multi Select React Native

---
