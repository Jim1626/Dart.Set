void main() {
  Set<String> name = {'Jim', 'Jemi', 'Joly', 'Aram', 'Niha', 'Nahiyan'};
  print(name);
  name.add('Nur');
  print(name);
  name.addAll({'Bristi', 'Jia', 'Papy', 'Joynob', 'Nurul', 'Hena'});
  print(name);
  print(name.runtimeType);
  name.remove('Jim');
  print(name);
  print(name.length);
  print(name.contains('Jim'));
  print(name.contains('Jemi'));
  print(name.containsAll({'Jim', 'Riyad', 'Aontor'}));
  print(name.containsAll({'Aram', 'Joly', 'Nur', 'Bristi', 'Papy'}));
  name.add('Jim');
  print(name.elementAt(2));
  print(name.elementAt(0));
  print(name.contains(123));
  print(name.length);
  print(name.first);
  print(name.last);
  Set<String> name2 = {
    'Priyanka',
    'Mashrur',
    'Rifat',
    'Arpita',
    'Roza',
    'Tushar',
    'Jim',
  };
  print(name2);
  print('Intersection Vlue:${name.intersection(name2)}');
  print('Union value:${name2.union(name)}');
}
