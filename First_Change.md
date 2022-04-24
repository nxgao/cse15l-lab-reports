        ArrayList<String> toReturn = new ArrayList<>();
        // find the next [, then find the ], then find the (, then read link upto next )
        int currentIndex = 0;
        while(currentIndex < markdown.length()) {
            int openBracket = markdown.indexOf("[", currentIndex);

            }
            int closeBracket = markdown.indexOf("]", openBracket);
  
            }
            int openParen = markdown.indexOf("(", closeBracket);
       
            }
            int closeParen = markdown.indexOf(")", openParen);
      
            }
            toReturn.add(markdown.substring(openParen + 1, closeParen));
            currentIndex = closeParen + 1;
        }
